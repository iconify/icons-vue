<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/zui445chq.css';
import '../../css/h/h-u5cozqr.css';
import '../../css/b/buaqtwbfz.css';
import '../../css/m/mli-fmb9z.css';
import '../../css/f/fxix_iiqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco zui445chq"/><path class="h-u5cozqr wm-k"/><path class="buaqtwbfz wm-k"/><path class="mli-fmb9z wm-a"/><path class="fxix_iiqi wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-archive-blueprint" /></template>
