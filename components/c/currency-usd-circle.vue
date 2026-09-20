<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj6qa494z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj6qa494z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-usd-circle" /></template>
