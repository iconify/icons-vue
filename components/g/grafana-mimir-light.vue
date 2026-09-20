<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w39ea_d2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w39ea_d2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-mimir-light" /></template>
