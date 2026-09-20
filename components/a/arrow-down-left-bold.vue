<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fck5xk6ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fck5xk6ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-down-left-bold" /></template>
