<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne86bmo9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne86bmo9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-party-mode" /></template>
