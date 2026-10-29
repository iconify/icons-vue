<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m4t0_gm4c.css';
import '../../css/p/p0lho5btv.css';
import '../../css/i/ie_33mcru.css';
import '../../css/p/pc6eh-ilv.css';
import '../../css/v/v7v_u0jql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m4t0_gm4c wm-k"/><path class="p0lho5btv wm-shadow"/><path class="ie_33mcru wm-k"/><path class="pc6eh-ilv wm-k"/><path class="v7v_u0jql wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dog-engrave" /></template>
