<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko2r1eq8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ko2r1eq8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:f-bold" /></template>
