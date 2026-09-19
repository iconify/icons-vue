<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyu5mfb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xyu5mfb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:e-outline" /></template>
