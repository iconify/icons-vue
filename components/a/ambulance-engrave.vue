<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b_z8-9b0c.css';
import '../../css/v/v6vm4shis.css';
import '../../css/q/qfd_dkbcz.css';
import '../../css/c/c2osk-a-j.css';
import '../../css/f/fbhxntbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b_z8-9b0c wm-k"/><path class="v6vm4shis wm-a"/><path class="qfd_dkbcz wm-shadow"/><path class="c2osk-a-j wm-k"/><path class="fbhxntbxi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ambulance-engrave" /></template>
