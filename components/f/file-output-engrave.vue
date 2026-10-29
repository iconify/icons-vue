<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/ti149fj5l.css';
import '../../css/x/xnqlj98sb.css';
import '../../css/r/rftpgmx8c.css';
import '../../css/l/lktwn-bjm.css';
import '../../css/i/ik22gveqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ti149fj5l wm-k"/><path class="wm-a xnqlj98sb"/><path class="rftpgmx8c wm-shadow"/><path class="lktwn-bjm wm-k"/><path class="ik22gveqy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-output-engrave" /></template>
