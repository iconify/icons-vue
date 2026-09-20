<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di-4csbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di-4csbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-slack" /></template>
