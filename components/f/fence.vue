<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4nf0t8ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="d4nf0t8ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:fence" /></template>
