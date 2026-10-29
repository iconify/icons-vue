<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p8u-xw6ko.css';
import '../../css/m/msg-wubhq.css';
import '../../css/w/w9ylbrb7f.css';
import '../../css/m/m6i-bjqet.css';
import '../../css/n/nuq9sybcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p8u-xw6ko wm-k"/><path class="msg-wubhq wm-a"/><path class="w9ylbrb7f wm-shadow"/><path class="m6i-bjqet wm-k"/><path class="nuq9sybcn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:indent-decrease-engrave" /></template>
