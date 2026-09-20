<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltyubtbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltyubtbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:app-badge" /></template>
