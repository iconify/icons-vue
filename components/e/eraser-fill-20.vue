<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-vhltmle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t-vhltmle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eraser-fill-20" /></template>
