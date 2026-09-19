<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdauo9bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="jdauo9bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:iron" /></template>
