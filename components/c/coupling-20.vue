<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oow9_6qcp.css';
import '../../css/d/d5ag-fmqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oow9_6qcp"/><path class="d5ag-fmqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coupling-20" /></template>
