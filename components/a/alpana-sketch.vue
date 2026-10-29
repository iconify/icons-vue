<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dokvabczg.css';
import '../../css/o/oas66acpd.css';
import '../../css/g/ggxowbc9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dokvabczg wm-k"/><path class="oas66acpd wm-k"/><path class="ggxowbc9f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alpana-sketch" /></template>
