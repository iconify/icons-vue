<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdn_9obuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdn_9obuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-1-bold" /></template>
