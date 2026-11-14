<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/w23k9ifmr.css';
import '../../css/z/zx2u6rbqg.css';
import '../../css/i/ivqiy5bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w23k9ifmr"/><path class="zx2u6rbqg"/><path class="ivqiy5bdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:home-charging" /></template>
