<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0nx8nhqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0nx8nhqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-clock-outline" /></template>
