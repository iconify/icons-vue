<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uye97lbbq.css';
import '../../css/g/gvhpknb0i.css';
import '../../css/g/gpo0x5mpy.css';
import '../../css/r/r0ei81btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="uye97lbbq"/><path clip-rule="evenodd" class="gvhpknb0i"/><path clip-rule="evenodd" class="gpo0x5mpy"/><path clip-rule="evenodd" class="r0ei81btz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:earth-americas" /></template>
