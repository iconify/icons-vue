<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-on1cbzr.css';
import '../../css/w/wzs-74bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-on1cbzr"/><path class="wzs-74bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-down-48-bold" /></template>
