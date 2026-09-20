<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvd31abxp.css';
import '../../css/e/e-1c61b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="e-1c61b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bar-chart-v" /></template>
