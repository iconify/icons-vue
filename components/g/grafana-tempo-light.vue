<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlv1xyrrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mlv1xyrrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-tempo-light" /></template>
