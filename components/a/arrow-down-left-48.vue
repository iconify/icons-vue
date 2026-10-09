<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uspm4fblj.css';
import '../../css/b/bq1dbsvyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uspm4fblj"/><path class="bq1dbsvyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-down-left-48" /></template>
