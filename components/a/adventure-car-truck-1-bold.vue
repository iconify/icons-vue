<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngl567b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngl567b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:adventure-car-truck-1-bold" /></template>
