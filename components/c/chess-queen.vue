<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_wppwbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_wppwbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chess-queen" /></template>
