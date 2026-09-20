<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iou8vqn-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iou8vqn-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:buffer" /></template>
