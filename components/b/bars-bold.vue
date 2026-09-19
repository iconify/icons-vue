<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8yf2jbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l8yf2jbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-bold" /></template>
