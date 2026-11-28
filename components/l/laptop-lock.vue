<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uebh2czab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uebh2czab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:laptop-lock" /></template>
