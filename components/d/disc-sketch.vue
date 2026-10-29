<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hj8fw8upx.css';
import '../../css/g/gv77zhbby.css';
import '../../css/f/fa4lrsbuw.css';
import '../../css/m/mdra5qi3b.css';
import '../../css/i/iztv2lhgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hj8fw8upx"/><path class="gv77zhbby wm-k"/><path class="fa4lrsbuw wm-k"/><path class="mdra5qi3b wm-a"/><circle class="iztv2lhgg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:disc-sketch" /></template>
