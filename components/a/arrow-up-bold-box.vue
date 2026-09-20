<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i04dlybtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i04dlybtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-bold-box" /></template>
