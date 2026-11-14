<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/baf6r5xsc.css';
import '../../css/f/fpneqjbpl.css';
import '../../css/k/k7qnch2qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="baf6r5xsc"/><circle class="fpneqjbpl"/><path class="k7qnch2qn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:charging-tariff" /></template>
