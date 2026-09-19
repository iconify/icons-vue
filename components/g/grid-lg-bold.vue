<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpuz_ibvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="dpuz_ibvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-lg-bold" /></template>
