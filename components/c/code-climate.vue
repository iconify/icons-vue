<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdmmufb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path transform="matrix(1.00302 0 0 1 -.05 0)" class="jdmmufb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:code-climate" /></template>
