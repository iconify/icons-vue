<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdsu42b0b.css';
import '../../css/z/z0-acdc1y.css';
import '../../css/x/x9_6abtpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="jdsu42b0b"/><path class="z0-acdc1y"/><path class="x9_6abtpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-definition" /></template>
