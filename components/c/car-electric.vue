<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/i5giqqahd.css';
import '../../css/q/q833gpbcf.css';
import '../../css/d/d4-ke6bbh.css';
import '../../css/n/n_i9t3l9h.css';
import '../../css/c/c71o25bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5giqqahd"/><circle class="q833gpbcf"/><circle class="d4-ke6bbh"/><path class="n_i9t3l9h"/><path class="c71o25bkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:car-electric" /></template>
