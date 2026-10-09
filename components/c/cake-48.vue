<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl5eyibfe.css';
import '../../css/y/y7rl90rrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nl5eyibfe"/><path class="y7rl90rrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cake-48" /></template>
