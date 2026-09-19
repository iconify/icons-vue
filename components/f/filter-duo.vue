<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4gi0yizr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="f4gi0yizr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:filter-duo" /></template>
