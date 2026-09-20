<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl8v88buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl8v88buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-pulse-outline" /></template>
