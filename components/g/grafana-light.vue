<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntexgpvsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntexgpvsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-light" /></template>
