<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt26bdcbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt26bdcbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-alert-outline" /></template>
