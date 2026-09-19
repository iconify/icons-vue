<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5fy0acnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="u5fy0acnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cogwheel-duo" /></template>
