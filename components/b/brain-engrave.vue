<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i-h3j9bzx.css';
import '../../css/p/pqvsh4b8l.css';
import '../../css/e/etqnjha5v.css';
import '../../css/n/n8dsurkgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i-h3j9bzx wm-k"/><path class="pqvsh4b8l wm-shadow"/><path class="etqnjha5v wm-k"/><path class="n8dsurkgv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-engrave" /></template>
