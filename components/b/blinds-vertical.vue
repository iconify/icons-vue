<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvc_kgbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvc_kgbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blinds-vertical" /></template>
