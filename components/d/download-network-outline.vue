<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy2tmbbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy2tmbbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-network-outline" /></template>
