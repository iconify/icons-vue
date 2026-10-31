<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/gspfgze7k.css';
import '../../css/g/ggozx156l.css';
import '../../css/t/tkf14mthh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="gspfgze7k wm-shadow"/><path class="ggozx156l wm-shadow"/><path class="tkf14mthh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:barcode" /></template>
