<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffy_fhb2a.css';
import '../../css/n/n8n104bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffy_fhb2a"/><path class="n8n104bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-efficiency-48-bold" /></template>
