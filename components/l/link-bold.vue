<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrw8ww-qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yrw8ww-qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:link-bold" /></template>
