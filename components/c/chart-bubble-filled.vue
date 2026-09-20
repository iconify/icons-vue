<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr7-1cb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr7-1cb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-bubble-filled" /></template>
