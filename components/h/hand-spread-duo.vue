<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ls7obax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="e_ls7obax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-spread-duo" /></template>
