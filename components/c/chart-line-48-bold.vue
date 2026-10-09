<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpel3hezc.css';
import '../../css/h/h31m63bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpel3hezc"/><path class="h31m63bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-line-48-bold" /></template>
