<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrk-757mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrk-757mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:danger-poison" /></template>
