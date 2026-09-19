<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8si_wb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8si_wb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dress-filled" /></template>
