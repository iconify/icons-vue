<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2zgibcpm.css';
import '../../css/z/zsaa8-ecz.css';
import '../../css/k/ku7tdocas.css';
import '../../css/l/lm00rvpau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u2zgibcpm"/><circle class="zsaa8-ecz"/><path class="ku7tdocas"/><path class="lm00rvpau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:apollo" /></template>
