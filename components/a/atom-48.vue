<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5c_hurfl.css';
import '../../css/o/oevu3r_8x.css';
import '../../css/k/koo_zccjj.css';
import '../../css/i/ijomgmbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i5c_hurfl"/><path class="oevu3r_8x"/><path class="koo_zccjj"/><path class="ijomgmbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:atom-48" /></template>
