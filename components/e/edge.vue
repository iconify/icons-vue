<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm1hixbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xm1hixbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:edge" /></template>
