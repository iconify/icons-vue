<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fvt7cccuv.css';
import '../../css/a/ab7dc2b0v.css';
import '../../css/c/c2-63vb0s.css';
import '../../css/q/qnf7a4b8e.css';
import '../../css/z/z7umnhr3t.css';
import '../../css/a/acoca_bst.css';
import '../../css/g/gtl72ce_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fvt7cccuv"/><path class="ab7dc2b0v wm-k"/><path class="c2-63vb0s wm-a"/><path class="qnf7a4b8e wm-s"/><path class="wm-k z7umnhr3t"/><path class="acoca_bst wm-a"/><path class="gtl72ce_a wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-pen-sketch" /></template>
