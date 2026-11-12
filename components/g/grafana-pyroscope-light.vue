<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/barzg96zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="barzg96zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-pyroscope-light" /></template>
