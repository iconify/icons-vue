<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tne_u8arr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="tne_u8arr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thin-right" /></template>
