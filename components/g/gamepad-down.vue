<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3emj7b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3emj7b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-down" /></template>
