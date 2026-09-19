<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uio_1y2lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="uio_1y2lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:fence-2" /></template>
