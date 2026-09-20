<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nik-3sbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nik-3sbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-tempo-dark" /></template>
