<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r50jkfbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="r50jkfbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:fire-wood" /></template>
