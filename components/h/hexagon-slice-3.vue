<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrmvrvlle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrmvrvlle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexagon-slice-3" /></template>
