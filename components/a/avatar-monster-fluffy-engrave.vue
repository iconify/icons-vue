<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xmh_htx7j.css';
import '../../css/h/hq4feobms.css';
import '../../css/v/v6yy0cbrr.css';
import '../../css/a/alio6gcxk.css';
import '../../css/l/lfeqacy5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xmh_htx7j"/><path class="hq4feobms wm-shadow"/><path class="v6yy0cbrr wm-k"/><path class="alio6gcxk wm-a"/><path class="lfeqacy5l wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-monster-fluffy-engrave" /></template>
