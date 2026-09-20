<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkbx_wbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkbx_wbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-center-vertical" /></template>
