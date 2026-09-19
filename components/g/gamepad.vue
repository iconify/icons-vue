<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tz8p96ses.css';
import '../../css/g/gjz44fbzs.css';
import '../../css/u/ufhycxbld.css';
import '../../css/j/j5doccc-u.css';
import '../../css/h/hqz_y6brn.css';
import '../../css/c/cyogq97kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="tz8p96ses"/><circle class="gjz44fbzs"/><circle class="ufhycxbld"/><path class="j5doccc-u"/><path class="hqz_y6brn"/><path class="cyogq97kg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:gamepad" /></template>
