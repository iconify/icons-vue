<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cw41ftbat.css';
import '../../css/d/d-9pp_qrb.css';
import '../../css/t/tmmgayb5u.css';
import '../../css/g/gz2kprb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cw41ftbat"/><path class="d-9pp_qrb wm-a"/><path class="tmmgayb5u wm-k"/><path class="gz2kprb8a wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-pdf-sketch" /></template>
