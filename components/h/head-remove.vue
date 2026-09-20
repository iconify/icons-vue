<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkm46bb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkm46bb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-remove" /></template>
