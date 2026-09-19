<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3_0dkbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h3_0dkbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:center-circle" /></template>
