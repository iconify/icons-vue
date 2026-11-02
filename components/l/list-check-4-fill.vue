<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvzlkhaez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvzlkhaez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-4-fill" /></template>
