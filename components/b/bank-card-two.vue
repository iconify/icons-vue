<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lcs_r-tfw.css';
import '../../css/v/vx77j8bxg.css';
import '../../css/x/xupzaydsh.css';
import '../../css/v/vzdx5c9so.css';
import '../../css/r/rh-s7xmlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="lcs_r-tfw"/><path class="vx77j8bxg"/><path class="xupzaydsh"/><path class="vzdx5c9so"/><path class="rh-s7xmlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bank-card-two" /></template>
