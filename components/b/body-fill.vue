<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqe43nhdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqe43nhdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:body-fill" /></template>
