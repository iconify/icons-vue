<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/civ01kben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="civ01kben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-line" /></template>
