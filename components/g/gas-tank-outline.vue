<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdyyz3t_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdyyz3t_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gas-tank-outline" /></template>
