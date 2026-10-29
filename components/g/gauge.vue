<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx8o3xwus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx8o3xwus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gauge" /></template>
