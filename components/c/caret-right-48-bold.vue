<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dda_dvbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dda_dvbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-right-48-bold" /></template>
