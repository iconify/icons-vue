<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_d2dzlwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="n_d2dzlwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:add-card" /></template>
