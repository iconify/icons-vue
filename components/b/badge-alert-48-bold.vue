<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si1030bhs.css';
import '../../css/e/e0fdkfvpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="si1030bhs"/><path class="e0fdkfvpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-alert-48-bold" /></template>
