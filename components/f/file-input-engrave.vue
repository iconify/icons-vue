<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m7ikj4brc.css';
import '../../css/t/thws8cc0h.css';
import '../../css/r/r-yigfbgu.css';
import '../../css/j/jnbx89z3f.css';
import '../../css/f/feq4sitoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m7ikj4brc wm-k"/><path class="thws8cc0h wm-a"/><path class="r-yigfbgu wm-shadow"/><path class="jnbx89z3f wm-k"/><path class="feq4sitoq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-input-engrave" /></template>
