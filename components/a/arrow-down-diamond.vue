<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3mkz8aiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3mkz8aiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-down-diamond" /></template>
