<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c--x9lbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="c--x9lbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:i-bold" /></template>
