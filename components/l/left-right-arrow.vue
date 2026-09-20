<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cefw7kb1y.css';
import '../../css/p/pfyahacbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cefw7kb1y"/><path class="pfyahacbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:left-right-arrow" /></template>
