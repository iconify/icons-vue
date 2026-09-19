<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmm9vsykl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmm9vsykl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:magnet-filled" /></template>
