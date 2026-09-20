<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfrlzyb-u.css';
import '../../css/q/q1ou_bnzh.css';
import '../../css/g/gy1gis3la.css';
import '../../css/k/kjiy61bvv.css';
import '../../css/v/vm_cohbnp.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/ow5hw0bji.css';
import '../../css/w/wlo6ihzyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="mfrlzyb-u"/><path class="q1ou_bnzh"/><path class="gy1gis3la"/><path class="kjiy61bvv"/><path class="vm_cohbnp"/><g class="jn8qy4bru"><path class="ow5hw0bji"/><path class="wlo6ihzyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:custard" /></template>
