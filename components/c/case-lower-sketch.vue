<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hisprwbpw.css';
import '../../css/j/jiv6tp4bc.css';
import '../../css/p/p2ghj7bdf.css';
import '../../css/r/rn1vb_b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hisprwbpw wm-k"/><path class="jiv6tp4bc wm-a"/><path class="p2ghj7bdf wm-k"/><path class="rn1vb_b2z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:case-lower-sketch" /></template>
