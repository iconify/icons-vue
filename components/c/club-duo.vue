<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0x3vwutg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="j0x3vwutg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:club-duo" /></template>
