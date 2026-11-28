<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_7_3len.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru_7_3len"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:air-conditioner-x" /></template>
