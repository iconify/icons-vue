<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as4yz9_fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="as4yz9_fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-donut-bold" /></template>
