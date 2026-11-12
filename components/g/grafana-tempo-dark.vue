<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0u0crbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0u0crbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-tempo-dark" /></template>
