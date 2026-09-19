<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew9ym6s6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ew9ym6s6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-circle-rycycle" /></template>
