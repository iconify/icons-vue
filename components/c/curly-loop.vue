<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfukdybcj.css';
import '../../css/e/e-3mmc50d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zfukdybcj"/><path class="e-3mmc50d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:curly-loop" /></template>
