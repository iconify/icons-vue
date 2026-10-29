<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/ws6xrvb7o.css';
import '../../css/t/tvqb1fbli.css';
import '../../css/y/yji0ufeoo.css';
import '../../css/t/tijvzhb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ws6xrvb7o"/><path class="tvqb1fbli wm-a"/><path class="wm-k yji0ufeoo"/><path class="tijvzhb8a wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bandage-sketch" /></template>
