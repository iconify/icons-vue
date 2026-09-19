<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-lx775bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="f-lx775bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:magnet-bold" /></template>
