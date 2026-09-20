<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7qys9bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7qys9bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arc-browser-fill" /></template>
