<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji2bvvmog.css';
import '../../css/c/ctgububiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ji2bvvmog"/><path class="ctgububiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calculation-alt" /></template>
