<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o0k_7tbwd.css';
import '../../css/r/r_619x8dw.css';
import '../../css/p/pfp6hfb3z.css';
import '../../css/e/ewb4c0zlw.css';
import '../../css/p/pht4mnbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o0k_7tbwd"/><path class="r_619x8dw wm-a"/><path class="pfp6hfb3z wm-s"/><path class="ewb4c0zlw"/><path class="pht4mnbru wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-monster-duo" /></template>
