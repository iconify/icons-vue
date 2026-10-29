<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tt4watg8b.css';
import '../../css/a/aefh-0lpq.css';
import '../../css/h/hc5bnmy4f.css';
import '../../css/z/zz6pr5t4p.css';
import '../../css/a/aai8m-gvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tt4watg8b wm-k"/><path class="aefh-0lpq wm-s"/><path class="hc5bnmy4f wm-shadow"/><path class="wm-k zz6pr5t4p"/><path class="aai8m-gvf wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-pull-request-closed-engrave" /></template>
