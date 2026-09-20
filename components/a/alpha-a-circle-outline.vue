<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te1q50b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te1q50b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-a-circle-outline" /></template>
