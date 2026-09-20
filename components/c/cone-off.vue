<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqinhgbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqinhgbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cone-off" /></template>
