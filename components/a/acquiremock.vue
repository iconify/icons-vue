<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0e4m_qgc.css';
import '../../css/x/xbfokwbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0e4m_qgc"/><path class="xbfokwbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:acquiremock" /></template>
