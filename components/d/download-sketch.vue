<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vcdd_bbfn.css';
import '../../css/v/v9qxvm3bb.css';
import '../../css/l/llxf78_xq.css';
import '../../css/v/v4b31vb2z.css';
import '../../css/l/ld-3ebcbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vcdd_bbfn"/><path class="v9qxvm3bb wm-k"/><path class="llxf78_xq wm-a"/><path class="v4b31vb2z wm-k"/><path class="ld-3ebcbh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:download-sketch" /></template>
