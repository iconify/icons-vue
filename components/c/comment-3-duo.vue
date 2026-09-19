<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9d3mpq3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="w9d3mpq3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-3-duo" /></template>
