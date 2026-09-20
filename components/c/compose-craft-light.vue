<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrr_ohbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrr_ohbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:compose-craft-light" /></template>
