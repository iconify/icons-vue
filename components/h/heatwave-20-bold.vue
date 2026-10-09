<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtrh8db_y.css';
import '../../css/q/qe94_hbwo.css';
import '../../css/c/ceu8rfb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mtrh8db_y"/><path class="qe94_hbwo"/><path class="ceu8rfb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heatwave-20-bold" /></template>
