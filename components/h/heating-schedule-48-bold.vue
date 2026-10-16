<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv_yx13wf.css';
import '../../css/h/hh9nw1bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xv_yx13wf"/><path class="hh9nw1bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heating-schedule-48-bold" /></template>
