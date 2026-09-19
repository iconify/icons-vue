<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omn6do9zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="omn6do9zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:array-decimal" /></template>
