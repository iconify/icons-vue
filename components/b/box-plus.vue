<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qawia2ile.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qawia2ile"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-plus" /></template>
