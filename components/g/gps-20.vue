<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhil_xbve.css';
import '../../css/h/hedtevnmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qhil_xbve"/><path class="hedtevnmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gps-20" /></template>
