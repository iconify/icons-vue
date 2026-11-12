<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z32qkbcxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z32qkbcxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-pyroscope-dark" /></template>
