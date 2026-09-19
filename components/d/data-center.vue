<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmwxaignu.css';
import '../../css/u/u86eo8b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zmwxaignu"/><path class="u86eo8b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-center" /></template>
