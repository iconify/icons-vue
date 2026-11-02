<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixxe14s0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixxe14s0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-ruble-2-line" /></template>
