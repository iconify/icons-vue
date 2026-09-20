<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lges67bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lges67bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-lock-open-outline" /></template>
