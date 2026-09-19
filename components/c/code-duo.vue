<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3hlx1zqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v3hlx1zqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code-duo" /></template>
