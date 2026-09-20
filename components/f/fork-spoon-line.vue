<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-7b-6vtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-7b-6vtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fork-spoon-line" /></template>
