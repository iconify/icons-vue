<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xguz53ivc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xguz53ivc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:info-variant-box" /></template>
