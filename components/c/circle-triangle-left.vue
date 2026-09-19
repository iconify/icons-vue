<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxajylj6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="jxajylj6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-triangle-left" /></template>
