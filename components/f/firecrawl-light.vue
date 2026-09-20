<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yun3io12r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yun3io12r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firecrawl-light" /></template>
