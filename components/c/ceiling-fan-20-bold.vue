<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkluasbjw.css';
import '../../css/m/moudosbgx.css';
import '../../css/o/olb-5xpso.css';
import '../../css/f/f-9u6xbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkluasbjw"/><path class="moudosbgx"/><path class="olb-5xpso"/><path class="f-9u6xbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ceiling-fan-20-bold" /></template>
