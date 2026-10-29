<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f0drbx22f.css';
import '../../css/p/p4dwao03s.css';
import '../../css/y/y95393_dl.css';
import '../../css/i/i-7a-zb9i.css';
import '../../css/o/o53n0ib2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f0drbx22f"/><path class="p4dwao03s wm-shadow"/><path class="y95393_dl"/><path class="i-7a-zb9i"/><path class="o53n0ib2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:database-engrave" /></template>
