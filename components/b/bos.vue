<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8wusz0vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i8wusz0vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bos" /></template>
