<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ansskgocr.css';
import '../../css/f/f_g898bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ansskgocr"/><path class="f_g898bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-git-compare" /></template>
