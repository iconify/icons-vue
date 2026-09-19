<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmsizop1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lmsizop1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:e" /></template>
