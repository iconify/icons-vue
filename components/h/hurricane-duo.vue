<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr-h46teo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dr-h46teo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hurricane-duo" /></template>
