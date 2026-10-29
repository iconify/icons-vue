<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pd-c8rb_b.css';
import '../../css/w/w_nj6nq5i.css';
import '../../css/g/gaam40bfx.css';
import '../../css/g/gdnuq8wfy.css';
import '../../css/g/g8_iol2hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pd-c8rb_b wm-k"/><path class="w_nj6nq5i wm-shadow"/><path class="gaam40bfx wm-k"/><path class="gdnuq8wfy wm-k"/><path class="g8_iol2hx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:binoculars-engrave" /></template>
