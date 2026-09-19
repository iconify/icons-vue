<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi5c-olvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wi5c-olvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-bar-outline" /></template>
