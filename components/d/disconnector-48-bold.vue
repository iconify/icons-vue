<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uww01kbpv.css';
import '../../css/i/ifa5gsbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uww01kbpv"/><path class="ifa5gsbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:disconnector-48-bold" /></template>
