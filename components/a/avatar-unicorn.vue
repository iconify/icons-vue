<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nob2a0bbf.css';
import '../../css/z/zj_xi2bhv.css';
import '../../css/p/pzcpqfb7d.css';
import '../../css/g/gk6g-yhok.css';
import '../../css/s/shsojk4vy.css';
import '../../css/x/x214md_bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nob2a0bbf"/><path class="wm-a zj_xi2bhv"/><path class="pzcpqfb7d"/><path class="gk6g-yhok wm-a"/><path class="shsojk4vy"/><path class="wm-a x214md_bs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-unicorn" /></template>
