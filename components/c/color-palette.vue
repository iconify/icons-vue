<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw4sg4bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dw4sg4bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:color-palette" /></template>
