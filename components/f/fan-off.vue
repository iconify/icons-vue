<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-i065b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-i065b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fan-off" /></template>
