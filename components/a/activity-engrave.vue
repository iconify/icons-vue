<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a471k1qjf.css';
import '../../css/f/f2uc4dbbl.css';
import '../../css/v/v53283b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a471k1qjf"/><path class="f2uc4dbbl wm-shadow"/><path class="v53283b0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:activity-engrave" /></template>
