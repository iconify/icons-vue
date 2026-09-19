<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_p_-yrff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y_p_-yrff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hash-duo" /></template>
