<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ario1abrj.css';
import '../../css/f/fi8t2tb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ario1abrj"/><path class="fi8t2tb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barrel-20-bold" /></template>
