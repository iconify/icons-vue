<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an4-ohbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="an4-ohbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lobehub-light" /></template>
