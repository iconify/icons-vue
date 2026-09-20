<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t33u9_b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t33u9_b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cyclone-outline" /></template>
