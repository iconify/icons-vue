<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tydndxb5d.css';
import '../../css/f/fjomncsfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tydndxb5d"/><path class="fjomncsfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:camera" /></template>
