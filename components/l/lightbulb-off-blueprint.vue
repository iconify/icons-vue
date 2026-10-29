<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/a6flzv85o.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/h/hyoz_h2gb.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="a6flzv85o wm-deco"/><path class="sdaucgb_l wm-deco"/><path class="hyoz_h2gb wm-k"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lightbulb-off-blueprint" /></template>
