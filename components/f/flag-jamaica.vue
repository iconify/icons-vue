<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_dxpcc8d.css';
import '../../css/t/tm9o1_bsg.css';
import '../../css/k/kyxecbcrt.css';
import '../../css/y/yvnwx-t5d.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<rect class="i_dxpcc8d"/><path class="tm9o1_bsg"/><path class="kyxecbcrt"/><path class="yvnwx-t5d"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-jamaica" /></template>
