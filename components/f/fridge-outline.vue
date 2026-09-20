<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drz4_tb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drz4_tb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-outline" /></template>
