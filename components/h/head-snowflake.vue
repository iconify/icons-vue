<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj_m6s_8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_m6s_8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-snowflake" /></template>
