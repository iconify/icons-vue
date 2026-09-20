<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7z5c_djq.css';
import '../../css/m/m76m0-g7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="r7z5c_djq"/><path class="m76m0-g7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:left-arrow" /></template>
