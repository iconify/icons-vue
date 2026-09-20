<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6a8w3bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6a8w3bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:flask" /></template>
