<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/psv_8pbss.css';
import '../../css/y/yvaeisbbi.css';
import '../../css/j/jxkkhtbrd.css';
import '../../css/p/p_lh2cbuk.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="psv_8pbss"/><path class="yvaeisbbi"/><path clip-rule="evenodd" class="jxkkhtbrd"/><path clip-rule="evenodd" class="p_lh2cbuk"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:earth-asia-circle" /></template>
