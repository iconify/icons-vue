<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe737fbnr.css';
import '../../css/q/qjfl8--kf.css';
import '../../css/u/u_0jnmbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fe737fbnr"/><path class="qjfl8--kf"/><path class="u_0jnmbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biogas-digester-48-bold" /></template>
