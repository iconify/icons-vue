<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r9-sysbhq.css';
import '../../css/l/ltqa-nbit.css';
import '../../css/k/k58yhuiry.css';
import '../../css/l/lcld7sb_p.css';
import '../../css/l/lkcu5tbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r9-sysbhq"/><path class="ltqa-nbit wm-k"/><path class="k58yhuiry wm-a"/><path class="lcld7sb_p wm-k"/><path class="lkcu5tbsw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-plus-sketch" /></template>
