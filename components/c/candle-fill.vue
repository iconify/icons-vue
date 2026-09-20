<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7lxw4bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7lxw4bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:candle-fill" /></template>
