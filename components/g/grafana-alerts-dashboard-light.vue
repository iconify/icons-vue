<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzg19p0qh.css';
import '../../css/q/q8n-7fbhw.css';
import '../../css/g/gy63hpboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzg19p0qh"/><path class="q8n-7fbhw"/><path class="gy63hpboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-alerts-dashboard-light" /></template>
