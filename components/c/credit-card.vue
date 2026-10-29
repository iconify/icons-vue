<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy1n90bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy1n90bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:credit-card" /></template>
