<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggvf3qbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ggvf3qbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-duo" /></template>
