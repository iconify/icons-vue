<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2nv_9ulb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2nv_9ulb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:grid-plus" /></template>
