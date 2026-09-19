<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owsatlbcf.css';
import '../../css/r/riavwwb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owsatlbcf"/><path class="riavwwb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-recommend" /></template>
