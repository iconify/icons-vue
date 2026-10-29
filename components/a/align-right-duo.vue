<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrr8yyb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrr8yyb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-right-duo" /></template>
