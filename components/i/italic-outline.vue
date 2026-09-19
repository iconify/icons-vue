<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8ah1-_tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="q8ah1-_tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:italic-outline" /></template>
