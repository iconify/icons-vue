<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jetbey4kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jetbey4kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:brightness-contrast" /></template>
