<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gnex1p8av.css';
import '../../css/n/noofjbbwm.css';
import '../../css/h/h1xtgdc1r.css';
import '../../css/z/zxdihacgb.css';
import '../../css/n/n-07r-b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gnex1p8av wm-deco"/><path class="noofjbbwm wm-deco"/><path class="h1xtgdc1r wm-deco"/><path class="wm-k zxdihacgb"/><path class="n-07r-b5s wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flask-conical-blueprint" /></template>
