<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zguq1dbdi.css';
import '../../css/a/aibqp5ysk.css';
import '../../css/a/a4ko41ypx.css';
import '../../css/j/jgr-ou_0r.css';
import '../../css/t/tvc6zw-sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zguq1dbdi"/><path class="aibqp5ysk wm-a"/><path class="a4ko41ypx wm-shadow"/><path class="jgr-ou_0r wm-k"/><path class="tvc6zw-sb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:highlighter-engrave" /></template>
