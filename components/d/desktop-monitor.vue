<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocpi9mk0u.css';
import '../../css/v/v031subhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocpi9mk0u"/><path class="v031subhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:desktop-monitor" /></template>
