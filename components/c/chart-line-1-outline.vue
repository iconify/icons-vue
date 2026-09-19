<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw0g4dbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xw0g4dbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-line-1-outline" /></template>
