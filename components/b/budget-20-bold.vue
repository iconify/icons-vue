<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iccsyvk3j.css';
import '../../css/q/qcnm51b0a.css';
import '../../css/s/sukfcubwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="qcnm51b0a"/><path class="sukfcubwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:budget-20-bold" /></template>
