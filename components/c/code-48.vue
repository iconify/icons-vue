<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm_-eumxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sm_-eumxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-48" /></template>
