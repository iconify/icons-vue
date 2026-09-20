<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrher560o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrher560o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:list" /></template>
