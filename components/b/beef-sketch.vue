<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jzy9u_b0c.css';
import '../../css/n/n7fxuac_e.css';
import '../../css/g/g3nhtmbdu.css';
import '../../css/z/z70t8ccqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jzy9u_b0c"/><path class="n7fxuac_e wm-a"/><path class="g3nhtmbdu wm-k"/><path class="wm-a z70t8ccqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:beef-sketch" /></template>
