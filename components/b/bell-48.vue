<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hosli1blv.css';
import '../../css/f/frcqirb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hosli1blv"/><path class="frcqirb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-48" /></template>
