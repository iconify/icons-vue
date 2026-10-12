<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzpmmxj6m.css';
import '../../css/e/ez71_mloi.css';
import '../../css/h/hc5gysb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jzpmmxj6m"/><path class="ez71_mloi"/><path class="hc5gysb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cnc-machine-48-bold" /></template>
