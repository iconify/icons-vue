<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d98p024yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="d98p024yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset-2-bold" /></template>
