<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhkq5mf7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uhkq5mf7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:canoe" /></template>
