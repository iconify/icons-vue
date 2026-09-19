<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o-v3vrb3z.css';
import '../../css/m/mhtdy_mav.css';
import '../../css/y/yb2lqrucn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-v3vrb3z"/><path class="mhtdy_mav"/><path class="yb2lqrucn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layers-logo" /></template>
