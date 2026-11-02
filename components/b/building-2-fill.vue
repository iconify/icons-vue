<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwiif3_bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwiif3_bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-2-fill" /></template>
