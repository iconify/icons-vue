<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rin2rdbyp.css';
import '../../css/y/yoo-x4z3f.css';
import '../../css/d/d27j7obsk.css';
import '../../css/q/qb_7iivgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rin2rdbyp"/><path class="yoo-x4z3f"/><path class="d27j7obsk"/><path class="qb_7iivgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-48-bold" /></template>
