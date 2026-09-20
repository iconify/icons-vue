<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lefr54bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lefr54bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:controller-device" /></template>
