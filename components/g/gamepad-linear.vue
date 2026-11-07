<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g9uxcsbqh.css';
import '../../css/r/rcgoqzxit.css';
import '../../css/j/jdkg2b8su.css';
import '../../css/i/i2afqdhro.css';
import '../../css/l/li08e_y6g.css';
import '../../css/k/kdceb2bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g9uxcsbqh"/><path class="rcgoqzxit"/><path class="jdkg2b8su"/><path class="i2afqdhro"/><path class="li08e_y6g"/><path class="kdceb2bpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-linear" /></template>
