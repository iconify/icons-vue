<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng0z8-bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng0z8-bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disabled-fill" /></template>
