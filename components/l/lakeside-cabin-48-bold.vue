<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ts8_bno.css';
import '../../css/m/mmtwl7b9d.css';
import '../../css/b/bpxnjdbqd.css';
import '../../css/f/fpzuy5-2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_ts8_bno"/><path class="mmtwl7b9d"/><path class="bpxnjdbqd"/><path class="fpzuy5-2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lakeside-cabin-48-bold" /></template>
