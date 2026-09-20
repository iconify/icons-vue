<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lqrlnfbtg.css';
import '../../css/m/mvk5gbb7t.css';
import '../../css/o/ov9m4obnk.css';
import '../../css/o/out3f_12j.css';
import '../../css/y/y-b52abdh.css';
import '../../css/r/rhe-p1bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle transform="rotate(-90 8.488 5)" class="lqrlnfbtg"/><circle transform="rotate(-90 8.488 12)" class="mvk5gbb7t"/><circle transform="rotate(-90 8.504 19)" class="ov9m4obnk"/><circle transform="rotate(-90 15.496 5)" class="out3f_12j"/><circle transform="rotate(-90 15.496 12)" class="y-b52abdh"/><circle transform="rotate(-90 15.512 19)" class="rhe-p1bon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grip-vertical-broken" /></template>
