<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qbxp0_3ai.css';
import '../../css/t/txqvo_bav.css';
import '../../css/k/k1xf4_bso.css';
import '../../css/e/ewou_cb1d.css';
import '../../css/b/bxvuuqbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qbxp0_3ai"/><path class="txqvo_bav"/><path class="k1xf4_bso wm-a"/><path class="ewou_cb1d"/><path class="bxvuuqbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-penguin-duo" /></template>
