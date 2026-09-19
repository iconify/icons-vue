<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqq00-9sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="eqq00-9sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:champion-cup" /></template>
