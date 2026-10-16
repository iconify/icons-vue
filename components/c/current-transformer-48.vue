<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc4olvb8c.css';
import '../../css/e/el8rvydxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fc4olvb8c"/><path class="el8rvydxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:current-transformer-48" /></template>
