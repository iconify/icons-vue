<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j89cktuio.css';
import '../../css/r/rgvx_5b3k.css';
import '../../css/i/io-5labnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j89cktuio"/><path class="rgvx_5b3k"/><path class="io-5labnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-alerts-dashboard-dark" /></template>
