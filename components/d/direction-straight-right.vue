<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umao54bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="umao54bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-straight-right" /></template>
