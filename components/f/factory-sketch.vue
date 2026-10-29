<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b6r623bpq.css';
import '../../css/w/wmfn8sbna.css';
import '../../css/e/ew51tmbbl.css';
import '../../css/c/cvqya5bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b6r623bpq"/><path class="wm-k wmfn8sbna"/><path class="ew51tmbbl wm-k"/><path class="cvqya5bkd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:factory-sketch" /></template>
