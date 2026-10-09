<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofzjtmbpe.css';
import '../../css/r/rm_v3ccms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ofzjtmbpe"/><path class="rm_v3ccms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-to-line-48" /></template>
