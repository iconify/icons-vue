<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txvu32bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txvu32bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:glasses" /></template>
