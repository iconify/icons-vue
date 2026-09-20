<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr4x_0bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr4x_0bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-left-circle" /></template>
