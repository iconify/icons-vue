<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij0-gp5hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ij0-gp5hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-3-bold" /></template>
