<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp0s8xg3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp0s8xg3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:4d" /></template>
