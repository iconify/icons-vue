<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufn6_c2nl.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/i/ixz9bpndl.css';
import '../../css/q/qp7u-0nuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ufn6_c2nl"/><circle class="e39ud6bwf"/><path class="ixz9bpndl"/><path class="qp7u-0nuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:improve-relevance" /></template>
