<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml2r52dge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ml2r52dge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aeterna-dark" /></template>
