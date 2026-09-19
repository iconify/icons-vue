<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zev4ttbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zev4ttbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:font-duo" /></template>
