<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sev_i2bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sev_i2bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-up-48" /></template>
