<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsmyp9b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsmyp9b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:led-variant-outline" /></template>
