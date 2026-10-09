<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbj7ts9zy.css';
import '../../css/s/sq_wf5bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rbj7ts9zy"/><path class="sq_wf5bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-left-48-bold" /></template>
