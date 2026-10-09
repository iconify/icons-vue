<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bulyt4ubp.css';
import '../../css/n/n6-nt1bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bulyt4ubp"/><path class="n6-nt1bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:egg-48-bold" /></template>
