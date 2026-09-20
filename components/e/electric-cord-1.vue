<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5_l8f-pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w5_l8f-pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:electric-cord-1" /></template>
