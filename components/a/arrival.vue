<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj2r8npqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kj2r8npqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrival" /></template>
