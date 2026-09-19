<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r5q18ebky.css';
import '../../css/a/a35do_bcy.css';
import '../../css/l/lqjv4_f5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r5q18ebky"/><path class="a35do_bcy"/><path class="lqjv4_f5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:location-04" /></template>
