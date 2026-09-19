<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr07urp8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wr07urp8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:headphones" /></template>
