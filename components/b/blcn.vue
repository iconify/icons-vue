<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb93fv_4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xb93fv_4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:blcn" /></template>
