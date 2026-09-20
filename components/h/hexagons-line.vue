<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d64zd6inn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d64zd6inn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagons-line" /></template>
