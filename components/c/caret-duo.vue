<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khmi4egos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="khmi4egos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:caret-duo" /></template>
