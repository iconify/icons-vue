<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmt3f4uja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rmt3f4uja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cut-in-half" /></template>
