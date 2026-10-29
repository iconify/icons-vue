<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tqw4osbms.css';
import '../../css/m/mti-algxy.css';
import '../../css/q/qj5h-ib_y.css';
import '../../css/e/ed1otty8l.css';
import '../../css/g/g660alolo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tqw4osbms"/><path class="mti-algxy wm-k"/><path class="qj5h-ib_y wm-a"/><path class="ed1otty8l wm-k"/><path class="g660alolo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:coffin-sketch" /></template>
