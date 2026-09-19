<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8_fmknql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8_fmknql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-3-square-bold" /></template>
