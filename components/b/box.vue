<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wob9zsz-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wob9zsz-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box" /></template>
