<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0dxb3_5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0dxb3_5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bidet" /></template>
