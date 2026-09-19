<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nch3szbem.css';
import '../../css/d/d6mnshidp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nch3szbem"/><path class="d6mnshidp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-query" /></template>
