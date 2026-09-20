<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmbb39pxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmbb39pxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:iframe-variable-outline" /></template>
