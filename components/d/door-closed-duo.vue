<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vghtvybyf.css';
import '../../css/s/smls78shz.css';
import '../../css/i/ic5g_yble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vghtvybyf"/><path class="smls78shz wm-a"/><path class="ic5g_yble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:door-closed-duo" /></template>
