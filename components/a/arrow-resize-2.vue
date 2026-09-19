<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv9jnn_gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tv9jnn_gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-resize-2" /></template>
