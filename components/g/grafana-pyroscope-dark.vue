<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpc8wfbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zpc8wfbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-pyroscope-dark" /></template>
