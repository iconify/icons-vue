<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnsr48_jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnsr48_jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloudy-night" /></template>
