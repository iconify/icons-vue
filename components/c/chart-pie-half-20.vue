<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1q-oibwe.css';
import '../../css/c/cp_m0ih6c.css';
import '../../css/q/qzsda2yxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g1q-oibwe"/><path class="cp_m0ih6c"/><path class="qzsda2yxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-pie-half-20" /></template>
