<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6vi645_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6vi645_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-2-line" /></template>
