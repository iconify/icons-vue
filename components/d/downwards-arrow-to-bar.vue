<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt-_m9ssp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lt-_m9ssp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:downwards-arrow-to-bar" /></template>
