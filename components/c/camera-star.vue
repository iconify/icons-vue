<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9rbi7bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9rbi7bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:camera-star" /></template>
