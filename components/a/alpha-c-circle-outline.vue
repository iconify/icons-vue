<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rockq_psm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rockq_psm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-c-circle-outline" /></template>
