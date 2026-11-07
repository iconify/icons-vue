<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnior1bog.css';
import '../../css/j/jy4h8gprs.css';
import '../../css/o/oy44jibka.css';
import '../../css/u/uv4oycn3f.css';
import '../../css/f/f5p3rgbsd.css';
import '../../css/l/lnf8p3bgz.css';
import '../../css/a/aui-jmtcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnior1bog"/><path class="jy4h8gprs"/><path class="oy44jibka"/><path class="uv4oycn3f"/><path class="f5p3rgbsd"/><path class="lnf8p3bgz"/><path class="aui-jmtcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-no-charge-bold-duotone" /></template>
