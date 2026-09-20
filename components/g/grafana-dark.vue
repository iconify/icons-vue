<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpa441bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jpa441bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana-dark" /></template>
