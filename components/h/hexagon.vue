<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-ob47bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-ob47bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hexagon" /></template>
