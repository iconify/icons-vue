<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amz719bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amz719bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:eraser" /></template>
