<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hjzzbm_-c.css';
import '../../css/x/xgqlv96ro.css';
import '../../css/o/o7p2p4bww.css';
import '../../css/x/xeo3lccmm.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="hjzzbm_-c"/><path clip-rule="evenodd" class="xgqlv96ro"/><path clip-rule="evenodd" class="o7p2p4bww"/><path class="xeo3lccmm"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:internet-circle-filled" /></template>
