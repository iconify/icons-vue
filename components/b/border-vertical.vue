<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-wx6dlth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l-wx6dlth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:border-vertical" /></template>
