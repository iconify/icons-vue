<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiwlsmqbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiwlsmqbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-send-outline" /></template>
