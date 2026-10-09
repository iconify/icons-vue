<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s84xoibnh.css';
import '../../css/d/dbhsu82qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s84xoibnh"/><path class="dbhsu82qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-empty-48" /></template>
