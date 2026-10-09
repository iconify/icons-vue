<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnmx-0bxp.css';
import '../../css/h/h84xrioyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mnmx-0bxp"/><path class="h84xrioyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-island-48" /></template>
