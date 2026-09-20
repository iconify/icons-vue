<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/sgfzyvn2h.css';
import '../../css/q/q9uu0nxvf.css';
import '../../css/c/clptpvbhb.css';
import '../../css/v/v4ok709ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sgfzyvn2h"/><path class="q9uu0nxvf"/><path class="clptpvbhb"/><path class="v4ok709ib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-tick" /></template>
