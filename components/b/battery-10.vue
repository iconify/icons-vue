<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1p0d4jsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1p0d4jsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-10" /></template>
