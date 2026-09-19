<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjzeqy2ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1664};
const content = `<path class="yjzeqy2ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:low-vision" /></template>
