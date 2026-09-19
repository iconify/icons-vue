<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9k_ldbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="g9k_ldbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:antenna-1" /></template>
