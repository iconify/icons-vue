<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ps-obut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q7ps-obut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:channels" /></template>
