<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lv_u3fbwv.css';
import '../../css/b/bej_0fbfn.css';
import '../../css/x/xlot_0bem.css';
import '../../css/m/mvtnklbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lv_u3fbwv"/><path class="bej_0fbfn"/><circle class="xlot_0bem"/><path class="mvtnklbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:camera-image-duotone" /></template>
