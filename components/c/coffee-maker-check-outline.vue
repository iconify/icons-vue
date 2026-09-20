<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu2cbnbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu2cbnbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coffee-maker-check-outline" /></template>
