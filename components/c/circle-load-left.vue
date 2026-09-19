<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp1gulu_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="jp1gulu_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-load-left" /></template>
