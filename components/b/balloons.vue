<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij0l8rbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij0l8rbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:balloons" /></template>
