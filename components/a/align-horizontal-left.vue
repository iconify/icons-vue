<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf3_r800o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3_r800o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:align-horizontal-left" /></template>
