<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf0779bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="hf0779bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-all-bold" /></template>
