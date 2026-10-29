<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wvvab8wgi.css';
import '../../css/w/w7vsx4bow.css';
import '../../css/p/pewiemwqu.css';
import '../../css/b/bbf80ib2m.css';
import '../../css/o/ols_87btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k wvvab8wgi"/><path class="w7vsx4bow wm-a"/><path class="pewiemwqu wm-shadow"/><path class="bbf80ib2m wm-k"/><path class="ols_87btu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-balloon-engrave" /></template>
