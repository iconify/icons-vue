<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isaosi6ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="isaosi6ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cross-christian-duo" /></template>
