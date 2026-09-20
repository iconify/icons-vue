<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fphliab1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fphliab1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hourglass-bold" /></template>
