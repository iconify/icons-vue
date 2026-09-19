<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu8kq7bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xu8kq7bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:line-outline" /></template>
