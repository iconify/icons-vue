<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpoyy9bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpoyy9bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:grafana-alloy" /></template>
