<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkvmf2k6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jkvmf2k6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cogwheel-outline" /></template>
