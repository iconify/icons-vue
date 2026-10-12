<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfv_tdfee.css';
import '../../css/e/ebopsbb7e.css';
import '../../css/g/gna13kh2l.css';
import '../../css/t/tcg3wkbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hfv_tdfee"/><path class="ebopsbb7e"/><path class="gna13kh2l"/><path class="tcg3wkbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drill-press-48-bold" /></template>
