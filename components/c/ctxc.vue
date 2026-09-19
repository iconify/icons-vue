<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef8m4s5nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ef8m4s5nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ctxc" /></template>
