<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arxc6mboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="arxc6mboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:download-3" /></template>
