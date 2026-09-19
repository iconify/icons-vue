<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkv56e61f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="zkv56e61f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:jump-forward" /></template>
