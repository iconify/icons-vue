<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tderinysh.css';
import '../../css/v/ve1blyb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tderinysh"/><path class="ve1blyb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kettle-48" /></template>
