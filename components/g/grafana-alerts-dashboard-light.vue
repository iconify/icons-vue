<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzg19p0qh.css';
import '../../css/f/f2eh-dbua.css';
import '../../css/a/aca60mb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzg19p0qh"/><path class="f2eh-dbua"/><path class="aca60mb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-alerts-dashboard-light" /></template>
