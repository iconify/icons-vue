<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iol1rclgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iol1rclgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:infrared-panel-48" /></template>
