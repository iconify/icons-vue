<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k0slrxj9a.css';
import '../../css/m/mxc1ddbwf.css';
import '../../css/c/coff_0a1c.css';
import '../../css/p/p568vbblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k0slrxj9a wm-k"/><path class="mxc1ddbwf wm-shadow"/><path class="coff_0a1c wm-k"/><path class="p568vbblp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:address-book-engrave" /></template>
