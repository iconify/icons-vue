<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v_-z67bjr.css';
import '../../css/f/fbtsz5b1h.css';
import '../../css/r/ra8smr1ma.css';
import '../../css/e/egx1okpdi.css';
import '../../css/c/chfexdi1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v_-z67bjr wm-k"/><path class="fbtsz5b1h wm-a"/><path class="ra8smr1ma wm-shadow"/><path class="egx1okpdi wm-k"/><path class="chfexdi1f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-first-engrave" /></template>
