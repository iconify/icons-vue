<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1acbcxl.css';
import '../../css/g/g127gxnyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="in1acbcxl"/><path class="g127gxnyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-bus-48" /></template>
