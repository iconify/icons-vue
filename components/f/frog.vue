<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dalgnjpdy.css';
import '../../css/v/vrunflstg.css';
import '../../css/x/xh5iej9vb.css';
import '../../css/e/eqpexpb_m.css';
import '../../css/y/yj617eybb.css';
import '../../css/t/tnolhfsay.css';
import '../../css/p/pl33t8bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dalgnjpdy"/><path class="vrunflstg"/><path class="xh5iej9vb"/><circle class="eqpexpb_m"/><circle class="yj617eybb"/><circle class="tnolhfsay"/><circle class="pl33t8bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:frog" /></template>
