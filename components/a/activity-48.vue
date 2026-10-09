<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk1kbxbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dk1kbxbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:activity-48" /></template>
