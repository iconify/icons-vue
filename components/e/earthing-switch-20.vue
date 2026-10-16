<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_mmmi5cu.css';
import '../../css/f/f-7xlbb5g.css';
import '../../css/q/qphgw4bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l_mmmi5cu"/><path class="f-7xlbb5g"/><path class="qphgw4bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earthing-switch-20" /></template>
