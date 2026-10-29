<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/immu0obxf.css';
import '../../css/s/sfcj4hbks.css';
import '../../css/n/n-2nd0bor.css';
import '../../css/v/vnt7_7l0x.css';
import '../../css/w/w2rv_8b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="immu0obxf wm-deco"/><path class="sfcj4hbks wm-deco"/><path class="n-2nd0bor wm-k"/><path class="vnt7_7l0x wm-a"/><path class="w2rv_8b5s wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-ghost-blueprint" /></template>
