<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sc3nweiyf.css';
import '../../css/s/sad7sib5y.css';
import '../../css/v/vlkk6aclm.css';
import '../../css/d/dzpvwud5r.css';
import '../../css/z/zrm_tfaxl.css';
import '../../css/y/y_fqobb9e.css';
import '../../css/r/rj2e_2hxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sc3nweiyf wm-k"/><path class="sad7sib5y wm-a"/><path class="vlkk6aclm wm-s"/><path class="dzpvwud5r wm-shadow"/><path class="wm-k zrm_tfaxl"/><path class="wm-a y_fqobb9e"/><path class="rj2e_2hxk wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:church-engrave" /></template>
