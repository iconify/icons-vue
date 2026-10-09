<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7o8wb3mz.css';
import '../../css/f/fcdm3_xoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x7o8wb3mz"/><path class="fcdm3_xoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-left-48" /></template>
