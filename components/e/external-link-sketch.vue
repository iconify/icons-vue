<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lotq6lz7v.css';
import '../../css/f/f68n4ubpd.css';
import '../../css/w/wushw_bfm.css';
import '../../css/f/f_a_1pbso.css';
import '../../css/h/hk66w8b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lotq6lz7v"/><path class="f68n4ubpd wm-k"/><path class="wm-a wushw_bfm"/><path class="f_a_1pbso wm-k"/><path class="hk66w8b5e wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:external-link-sketch" /></template>
