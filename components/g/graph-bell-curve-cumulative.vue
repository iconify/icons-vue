<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hor504bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hor504bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:graph-bell-curve-cumulative" /></template>
