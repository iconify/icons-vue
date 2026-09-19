<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq-ba649u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zq-ba649u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:graduation-cap" /></template>
