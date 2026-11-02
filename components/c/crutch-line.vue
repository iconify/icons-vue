<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl4kjq-4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl4kjq-4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:crutch-line" /></template>
