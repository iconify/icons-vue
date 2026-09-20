<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czzkpnbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czzkpnbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:disk-player" /></template>
