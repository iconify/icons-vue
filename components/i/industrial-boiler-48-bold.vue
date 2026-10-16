<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzeh33brv.css';
import '../../css/k/k2l56tbqb.css';
import '../../css/i/ihmii9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gzeh33brv"/><path class="k2l56tbqb"/><path class="ihmii9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:industrial-boiler-48-bold" /></template>
