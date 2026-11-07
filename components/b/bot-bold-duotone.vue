<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvbcrablp.css';
import '../../css/l/lwrg85til.css';
import '../../css/v/vcu04ebhz.css';
import '../../css/i/iysev6bne.css';
import '../../css/d/dxnrye12r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvbcrablp"/><path class="lwrg85til"/><path class="vcu04ebhz"/><path class="iysev6bne"/><path class="dxnrye12r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bot-bold-duotone" /></template>
