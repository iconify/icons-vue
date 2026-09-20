<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt6bjmk9e.css';
import '../../css/e/e77jw6bhj.css';
import '../../css/m/m-0u4sbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tt6bjmk9e"/><path class="e77jw6bhj"/><path class="m-0u4sbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:grain" /></template>
