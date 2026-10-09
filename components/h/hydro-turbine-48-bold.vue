<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjt_z5brr.css';
import '../../css/g/gkrmg0bdd.css';
import '../../css/w/w8f5y0ctf.css';
import '../../css/e/e27-1tvtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zjt_z5brr"/><path class="gkrmg0bdd"/><path class="w8f5y0ctf"/><path class="e27-1tvtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-turbine-48-bold" /></template>
