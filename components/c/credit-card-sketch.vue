<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rnabr02rn.css';
import '../../css/g/gi1cpjbgb.css';
import '../../css/f/f878cac8p.css';
import '../../css/l/ldpho9bqh.css';
import '../../css/p/p0qrfj54q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rnabr02rn wm-k"/><path class="gi1cpjbgb wm-k"/><path class="f878cac8p wm-k"/><path class="ldpho9bqh wm-a"/><path class="p0qrfj54q wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:credit-card-sketch" /></template>
