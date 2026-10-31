<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwh_5cbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwh_5cbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-close-corner-round" /></template>
