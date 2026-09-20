<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6la5k3mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6la5k3mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-fit" /></template>
