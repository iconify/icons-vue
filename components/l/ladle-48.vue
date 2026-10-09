<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq1cssb6m.css';
import '../../css/e/ef6i17ddi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iq1cssb6m"/><path class="ef6i17ddi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladle-48" /></template>
