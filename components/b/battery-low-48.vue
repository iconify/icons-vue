<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s84xoibnh.css';
import '../../css/d/dbhsu82qc.css';
import '../../css/g/gc26xwksp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s84xoibnh"/><path class="dbhsu82qc"/><path class="gc26xwksp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-low-48" /></template>
