<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d62az0bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d62az0bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-off" /></template>
