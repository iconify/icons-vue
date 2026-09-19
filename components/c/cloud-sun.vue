<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f80hj5bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="f80hj5bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cloud-sun" /></template>
