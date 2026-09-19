<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kod7n39qq.css';
import '../../css/s/sh8kg65pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kod7n39qq"/><path class="sh8kg65pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:klown" /></template>
