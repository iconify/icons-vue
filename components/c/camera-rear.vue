<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe0-w_bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe0-w_bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-rear" /></template>
