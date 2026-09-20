<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcb9nhxcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcb9nhxcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-off" /></template>
