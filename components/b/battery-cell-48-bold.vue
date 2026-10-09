<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlsjaz2ur.css';
import '../../css/m/mp2bmtb4q.css';
import '../../css/h/hfhgd-2kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jlsjaz2ur"/><path class="mp2bmtb4q"/><path class="hfhgd-2kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cell-48-bold" /></template>
