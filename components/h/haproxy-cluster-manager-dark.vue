<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzmn72bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yzmn72bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:haproxy-cluster-manager-dark" /></template>
