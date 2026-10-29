<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z80o90bnu.css';
import '../../css/c/c7pts9b4m.css';
import '../../css/e/e-pbxlb-r.css';
import '../../css/u/uq6pxgb_j.css';
import '../../css/c/cs2ofc7il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z80o90bnu"/><path class="c7pts9b4m wm-k"/><path class="e-pbxlb-r wm-a"/><path class="uq6pxgb_j wm-k"/><path class="cs2ofc7il wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-x-sketch" /></template>
