<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyi-sxdur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="cyi-sxdur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:left-justify" /></template>
