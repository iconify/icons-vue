<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvw6ur04b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rvw6ur04b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:line-two-angle-point" /></template>
