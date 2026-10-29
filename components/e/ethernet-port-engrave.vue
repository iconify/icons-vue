<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kwp6q9bxu.css';
import '../../css/f/fotuh8qtd.css';
import '../../css/h/hm38-ccpa.css';
import '../../css/f/f3tg6ebbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kwp6q9bxu wm-k"/><path class="fotuh8qtd wm-shadow"/><path class="hm38-ccpa wm-k"/><path class="f3tg6ebbt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ethernet-port-engrave" /></template>
