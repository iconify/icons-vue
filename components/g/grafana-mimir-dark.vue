<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbbm33x5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbbm33x5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-mimir-dark" /></template>
