<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/x/x49uqwbjn.css';
import '../../css/b/brfohtb0o.css';
import '../../css/o/oun623fgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco x49uqwbjn"/><path class="brfohtb0o wm-deco"/><path class="oun623fgc wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:barcode-blueprint" /></template>
