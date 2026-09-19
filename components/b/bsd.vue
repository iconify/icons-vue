<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-37kwbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e-37kwbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bsd" /></template>
