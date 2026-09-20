<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kok2lcctq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kok2lcctq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:aurora" /></template>
