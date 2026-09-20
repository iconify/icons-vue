<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxfxniffl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxfxniffl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-rotation-angle-up" /></template>
