<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz-knsbvd.css';
import '../../css/l/lj7gdpblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vz-knsbvd"/><path class="lj7gdpblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heatwave-48-bold" /></template>
