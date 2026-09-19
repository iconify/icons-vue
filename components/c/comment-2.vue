<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3q7igb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="d3q7igb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-2" /></template>
