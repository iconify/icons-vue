<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwr4clbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cwr4clbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hexagon-bold" /></template>
