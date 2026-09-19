<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h20a15_6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="h20a15_6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-left-right" /></template>
