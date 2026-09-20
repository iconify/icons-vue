<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr0yipbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wr0yipbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:exe" /></template>
