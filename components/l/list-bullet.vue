<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um9_oznhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="um9_oznhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:list-bullet" /></template>
