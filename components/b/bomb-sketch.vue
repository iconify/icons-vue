<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f1zgeeb4m.css';
import '../../css/u/u7v3onpgn.css';
import '../../css/x/x6znfw3hn.css';
import '../../css/a/afoe1d7we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f1zgeeb4m"/><path class="u7v3onpgn wm-k"/><path class="wm-a x6znfw3hn"/><path class="afoe1d7we wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bomb-sketch" /></template>
