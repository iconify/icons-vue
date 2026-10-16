<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qntmgtbht.css';
import '../../css/m/mfqrv5y5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qntmgtbht"/><path class="mfqrv5y5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:and-gate-20-bold" /></template>
