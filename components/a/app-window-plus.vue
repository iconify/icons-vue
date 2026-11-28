<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjr8ncbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjr8ncbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:app-window-plus" /></template>
