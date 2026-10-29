<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t_g72-b9s.css';
import '../../css/k/kdi-73b5e.css';
import '../../css/v/vahbrmb-p.css';
import '../../css/i/isb-x7b4z.css';
import '../../css/s/s1afeeb0i.css';
import '../../css/t/t24d_rbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t_g72-b9s wm-k"/><path class="kdi-73b5e wm-a"/><path class="vahbrmb-p wm-shadow"/><path class="isb-x7b4z wm-k"/><path class="s1afeeb0i wm-a"/><path class="t24d_rbut wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:code-engrave" /></template>
