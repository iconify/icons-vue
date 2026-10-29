<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fm5u9g7-b.css';
import '../../css/g/g4q_d4blp.css';
import '../../css/r/r1i2fkb-z.css';
import '../../css/z/z0l13u7rz.css';
import '../../css/e/eumle_byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fm5u9g7-b wm-k"/><path class="g4q_d4blp wm-a"/><path class="r1i2fkb-z wm-shadow"/><path class="wm-k z0l13u7rz"/><path class="eumle_byd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:apple-engrave" /></template>
