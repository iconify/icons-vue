<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzrwobbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzrwobbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-cog-outline" /></template>
