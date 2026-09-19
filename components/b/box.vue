<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og8nmqhzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="og8nmqhzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:box" /></template>
