<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cap4h-y1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cap4h-y1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hourglass-outline" /></template>
