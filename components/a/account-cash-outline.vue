<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydlganihh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydlganihh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-cash-outline" /></template>
