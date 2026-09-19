<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/innh25fao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="innh25fao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-slash-filled" /></template>
