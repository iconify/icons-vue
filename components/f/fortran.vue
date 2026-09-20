<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co37yjsqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="co37yjsqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:fortran" /></template>
