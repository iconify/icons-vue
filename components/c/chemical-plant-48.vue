<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrvslrbcn.css';
import '../../css/t/t1ta_fbcc.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qrvslrbcn"/><path class="t1ta_fbcc"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chemical-plant-48" /></template>
