<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elie8f57q.css';
import '../../css/o/ov2o_f2qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="elie8f57q"/><path class="ov2o_f2qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:boiler-20-bold" /></template>
