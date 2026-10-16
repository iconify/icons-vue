<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezwopb-j.css';
import '../../css/i/ie_5nbw3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="ie_5nbw3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-warning-48" /></template>
