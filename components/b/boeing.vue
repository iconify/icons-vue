<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy01kxb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy01kxb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:boeing" /></template>
