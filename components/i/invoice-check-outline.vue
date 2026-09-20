<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsz0_wapm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsz0_wapm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-check-outline" /></template>
