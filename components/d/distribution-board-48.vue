<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvyikx3qg.css';
import '../../css/f/fwh01mbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qvyikx3qg"/><path class="fwh01mbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribution-board-48" /></template>
