<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwvx4yb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwvx4yb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-circles-group" /></template>
