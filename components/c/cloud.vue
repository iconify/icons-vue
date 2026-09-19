<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvk5fntyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="bvk5fntyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cloud" /></template>
