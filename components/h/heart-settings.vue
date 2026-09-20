<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4ubt_yrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4ubt_yrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-settings" /></template>
