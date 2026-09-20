<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrsarig3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrsarig3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-figma-solid" /></template>
