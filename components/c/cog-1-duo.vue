<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2_yd-19i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y2_yd-19i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cog-1-duo" /></template>
