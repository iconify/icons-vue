<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsahk5bgt.css';
import '../../css/d/d1j7k6bho.css';
import '../../css/h/hae377b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qsahk5bgt"/><path class="d1j7k6bho"/><path class="hae377b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hourglass-48-bold" /></template>
