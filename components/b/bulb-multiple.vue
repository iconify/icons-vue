<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xug077bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xug077bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bulb-multiple" /></template>
