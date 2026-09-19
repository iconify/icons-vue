<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjyotb2gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jjyotb2gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:exclamation" /></template>
