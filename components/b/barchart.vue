<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcpug3b7d.css';
import '../../css/d/d87ud_bsv.css';
import '../../css/a/a_bbs6b7a.css';
import '../../css/b/boq1zg2ir.css';
import '../../css/r/rfmo84bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcpug3b7d"/><path class="d87ud_bsv"/><path class="a_bbs6b7a"/><path class="boq1zg2ir"/><path class="rfmo84bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:barchart" /></template>
