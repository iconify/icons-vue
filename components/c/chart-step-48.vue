<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utf77lbef.css';
import '../../css/l/lrtwh708v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="lrtwh708v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-step-48" /></template>
