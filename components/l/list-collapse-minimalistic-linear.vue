<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l7y12ieah.css';
import '../../css/v/v8tx6ieir.css';
import '../../css/a/a-d731ccj.css';
import '../../css/h/hrpb3z6mg.css';
import '../../css/m/meafjacfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l7y12ieah"/><path class="v8tx6ieir"/><path class="a-d731ccj"/><path class="hrpb3z6mg"/><path class="meafjacfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-collapse-minimalistic-linear" /></template>
