<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnwo8kn8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xnwo8kn8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:l-bold" /></template>
