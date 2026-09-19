<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5dva-b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t5dva-b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:link-1-bold" /></template>
