<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpg1m5ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpg1m5ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-vertical-fill-round" /></template>
