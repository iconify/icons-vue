<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j89cktuio.css';
import '../../css/t/tx20ehscf.css';
import '../../css/h/h4zt9xb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j89cktuio"/><path class="tx20ehscf"/><path class="h4zt9xb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-alerts-dashboard-dark" /></template>
