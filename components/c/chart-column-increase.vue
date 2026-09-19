<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcgcscb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="mcgcscb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:chart-column-increase" /></template>
