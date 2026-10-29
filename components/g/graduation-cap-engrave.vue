<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b4i-chjwh.css';
import '../../css/f/fttdwcc-b.css';
import '../../css/y/ybto86sfo.css';
import '../../css/t/ttlc-na8v.css';
import '../../css/p/po6tsm3ou.css';
import '../../css/l/l2miw0nqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b4i-chjwh wm-k"/><path class="fttdwcc-b wm-a"/><path class="wm-shadow ybto86sfo"/><path class="ttlc-na8v wm-k"/><path class="po6tsm3ou wm-k"/><path class="l2miw0nqo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:graduation-cap-engrave" /></template>
