<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x_32s8b6z.css';
import '../../css/y/yri-nfb2u.css';
import '../../css/a/aa7exib7i.css';
import '../../css/j/jura4nbok.css';
import '../../css/f/fcpcu9i2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x_32s8b6z"/><path class="wm-a yri-nfb2u"/><path class="aa7exib7i wm-shadow"/><path class="jura4nbok wm-k"/><path class="fcpcu9i2b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:magnet-engrave" /></template>
