<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/ct9lq-phd.css';
import '../../css/n/npzbi206w.css';
import '../../css/l/lqkmkym5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ct9lq-phd"/><circle class="npzbi206w"/><path class="lqkmkym5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chess-bishop" /></template>
