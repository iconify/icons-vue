<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdsmi1bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vdsmi1bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-light" /></template>
