<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i9tt7iemb.css';
import '../../css/l/la1da1bon.css';
import '../../css/z/z68_6dbbs.css';
import '../../css/d/dti5vzuij.css';
import '../../css/d/ds_glz1tz.css';
import '../../css/m/m4zyr0b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i9tt7iemb"/><path class="la1da1bon wm-k"/><path class="wm-k z68_6dbbs"/><path class="dti5vzuij wm-a"/><path class="ds_glz1tz wm-a"/><path class="m4zyr0b5h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-minus-sketch" /></template>
