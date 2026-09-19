<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ors6v7rpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ors6v7rpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:leftwards-arrow-to-bar" /></template>
