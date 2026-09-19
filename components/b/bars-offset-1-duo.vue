<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfw55jhmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vfw55jhmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset-1-duo" /></template>
