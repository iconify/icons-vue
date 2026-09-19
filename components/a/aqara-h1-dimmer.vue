<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpy08yb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpy08yb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-h1-dimmer" /></template>
