<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tty_6yy-t.css';
import '../../css/o/ot82azbfv.css';
import '../../css/z/zhfwy2bbl.css';
import '../../css/o/o_vwuj4ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tty_6yy-t"/><path class="ot82azbfv"/><path class="zhfwy2bbl"/><path class="o_vwuj4ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biomass-20-bold" /></template>
