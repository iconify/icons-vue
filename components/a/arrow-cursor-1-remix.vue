<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khndaxb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="khndaxb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-cursor-1-remix" /></template>
