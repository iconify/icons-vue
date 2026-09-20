<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5mnpzb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5mnpzb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eraser-square-filled" /></template>
