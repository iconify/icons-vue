<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbtry84gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbtry84gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heart-pulse-alert" /></template>
