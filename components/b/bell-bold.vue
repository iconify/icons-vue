<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m92zv-bjj.css';
import '../../css/h/h71b5fbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m92zv-bjj"/><path class="h71b5fbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-bold" /></template>
