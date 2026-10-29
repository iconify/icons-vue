<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/zui445chq.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/h/h-u5cozqr.css';
import '../../css/f/fq8s3hbff.css';
import '../../css/f/fxix_iiqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco zui445chq"/><path class="sdaucgb_l wm-deco"/><path class="h-u5cozqr wm-k"/><path class="fq8s3hbff wm-a"/><path class="fxix_iiqi wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-up-blueprint" /></template>
