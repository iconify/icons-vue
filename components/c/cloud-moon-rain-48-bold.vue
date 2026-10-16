<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njwg_cbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="njwg_cbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-moon-rain-48-bold" /></template>
