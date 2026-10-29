<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nlbfqsa6d.css';
import '../../css/t/t8pf0gk5g.css';
import '../../css/j/jqg226l7r.css';
import '../../css/h/hfgrowsuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nlbfqsa6d"/><path class="t8pf0gk5g wm-k"/><path class="jqg226l7r wm-a"/><path class="hfgrowsuv wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:broom-sketch" /></template>
