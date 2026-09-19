<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz-q7k4cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mz-q7k4cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:divide" /></template>
