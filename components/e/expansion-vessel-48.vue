<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-cpeb9h.css';
import '../../css/e/ekaxy2bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ps-cpeb9h"/><path class="ekaxy2bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:expansion-vessel-48" /></template>
