<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipgay6bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipgay6bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cigarette" /></template>
