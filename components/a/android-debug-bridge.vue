<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbm8uzbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbm8uzbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:android-debug-bridge" /></template>
