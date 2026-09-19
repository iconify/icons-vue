<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz5zt-bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":435,"height":512};
const content = `<path class="nz5zt-bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:apiextractor" /></template>
