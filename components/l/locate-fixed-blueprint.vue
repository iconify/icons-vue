<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lwkt2g_ty.css';
import '../../css/m/miijncbwe.css';
import '../../css/x/x6ru6ciza.css';
import '../../css/w/wh0zujbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lwkt2g_ty wm-deco"/><path class="miijncbwe wm-deco"/><path class="wm-k x6ru6ciza"/><path class="wh0zujbon wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:locate-fixed-blueprint" /></template>
