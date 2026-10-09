<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meve8lt-m.css';
import '../../css/l/l4lrodbjn.css';
import '../../css/y/ywo35nt_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="meve8lt-m"/><path class="l4lrodbjn"/><path class="ywo35nt_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-tent-48" /></template>
