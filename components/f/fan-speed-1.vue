<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1jm6f-dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1jm6f-dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fan-speed-1" /></template>
