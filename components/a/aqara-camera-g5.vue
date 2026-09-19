<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6x9rgtoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6x9rgtoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-camera-g5" /></template>
