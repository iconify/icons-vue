<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrhuz0bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrhuz0bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cloud" /></template>
