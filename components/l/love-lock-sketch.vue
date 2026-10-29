<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fxry8qb4t.css';
import '../../css/f/fhn7b6sgb.css';
import '../../css/s/spzn2d-cx.css';
import '../../css/o/ot9uu0bvw.css';
import '../../css/t/t6ecn0b2f.css';
import '../../css/p/ptbvm8vxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fxry8qb4t"/><path class="fhn7b6sgb wm-k"/><path class="spzn2d-cx wm-k"/><circle class="ot9uu0bvw wm-k"/><path class="t6ecn0b2f wm-k"/><path class="ptbvm8vxq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:love-lock-sketch" /></template>
