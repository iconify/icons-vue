<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km9at56kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="km9at56kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:computer-desktop" /></template>
