<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7k60fmpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7k60fmpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-1-bold" /></template>
