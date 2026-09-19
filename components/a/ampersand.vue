<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um1d8cbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="um1d8cbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:ampersand" /></template>
