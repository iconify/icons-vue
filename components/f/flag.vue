<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrxy_3b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrxy_3b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flag" /></template>
