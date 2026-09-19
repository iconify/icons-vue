<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0f3mspza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g0f3mspza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-left-a" /></template>
