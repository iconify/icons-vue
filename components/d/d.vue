<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri3dx_bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ri3dx_bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:d" /></template>
