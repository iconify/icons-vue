<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tdkzpcchx.css';
import '../../css/s/sp3d1db5j.css';
import '../../css/c/ci-x2rghr.css';
import '../../css/c/cp-21rdbm.css';
import '../../css/q/qjq0m1byh.css';
import '../../css/e/ey1deybvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="tdkzpcchx"/><path class="sp3d1db5j"/><path class="ci-x2rghr"/><path clip-rule="evenodd" class="cp-21rdbm"/><path class="qjq0m1byh"/><path class="ey1deybvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:house-water" /></template>
