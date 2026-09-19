<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyw-t95-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qyw-t95-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset-bold" /></template>
