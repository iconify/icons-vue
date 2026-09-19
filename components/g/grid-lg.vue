<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5ln8m42s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l5ln8m42s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-lg" /></template>
