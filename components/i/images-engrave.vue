<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gxr1a2smb.css';
import '../../css/o/osimhab3r.css';
import '../../css/h/hq97iacbj.css';
import '../../css/b/b8gdax63a.css';
import '../../css/u/u11d_bcbf.css';
import '../../css/j/j3ihixg7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gxr1a2smb wm-k"/><path class="osimhab3r wm-a"/><path class="hq97iacbj wm-shadow"/><path class="b8gdax63a wm-k"/><path class="u11d_bcbf wm-k"/><path class="j3ihixg7r wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:images-engrave" /></template>
