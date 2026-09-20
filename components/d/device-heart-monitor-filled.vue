<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd5n7t3xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd5n7t3xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-heart-monitor-filled" /></template>
