<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a6cwelbwj.css';
import '../../css/e/es45psbqk.css';
import '../../css/b/beoe_ii1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a6cwelbwj"/><path class="es45psbqk wm-shadow"/><path class="beoe_ii1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:butterfly-engrave" /></template>
