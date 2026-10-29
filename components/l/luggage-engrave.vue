<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eo_fdcq_l.css';
import '../../css/j/jqxm5ebsw.css';
import '../../css/x/xdj3f2nra.css';
import '../../css/p/pr4hfob0i.css';
import '../../css/n/ndggxmqsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eo_fdcq_l wm-k"/><path class="jqxm5ebsw wm-a"/><path class="wm-shadow xdj3f2nra"/><path class="pr4hfob0i wm-k"/><path class="ndggxmqsd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:luggage-engrave" /></template>
