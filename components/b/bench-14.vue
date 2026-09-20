<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayk2_7bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ayk2_7bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bench-14" /></template>
