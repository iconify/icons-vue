<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylb0d8b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ylb0d8b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-gitlab" /></template>
