<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at_qv4_-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="at_qv4_-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gantt-chart-solid" /></template>
