<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hbwf3nbad.css';
import '../../css/x/xupe0ib4r.css';
import '../../css/i/i2h8khgsx.css';
import '../../css/o/o75ukvbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hbwf3nbad wm-deco"/><path class="wm-deco xupe0ib4r"/><path class="i2h8khgsx wm-k"/><circle class="o75ukvbpp wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-dino-blueprint" /></template>
