<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z6ckjlypu.css';
import '../../css/o/o84qkd8vw.css';
import '../../css/l/lh8b35twf.css';
import '../../css/o/odzqh-bcc.css';
import '../../css/z/zkigybchi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k z6ckjlypu"/><path class="o84qkd8vw wm-a"/><path class="lh8b35twf wm-shadow"/><path class="odzqh-bcc wm-k"/><path class="wm-a zkigybchi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hash-engrave" /></template>
