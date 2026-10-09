<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehrmklbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ehrmklbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hexagon-48" /></template>
