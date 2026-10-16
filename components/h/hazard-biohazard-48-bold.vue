<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2mjsubix.css';
import '../../css/p/p5jryccsb.css';
import '../../css/y/y76vbmdhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="p5jryccsb"/><path class="y76vbmdhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-biohazard-48-bold" /></template>
