<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqh3i2bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqh3i2bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-2-line" /></template>
