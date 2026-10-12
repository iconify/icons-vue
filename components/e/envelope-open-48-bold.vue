<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8b9igb2o.css';
import '../../css/d/d3c0vccgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v8b9igb2o"/><path class="d3c0vccgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:envelope-open-48-bold" /></template>
