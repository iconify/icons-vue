<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1gdnmbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="x1gdnmbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:die-2-bold" /></template>
