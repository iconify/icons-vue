<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/odcznobbg.css';
import '../../css/q/qllxnxb-j.css';
import '../../css/a/arkab0lto.css';
import '../../css/k/k3mij9nwy.css';
import '../../css/k/kjl88pbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="odcznobbg wm-k"/><path class="qllxnxb-j wm-a"/><path class="arkab0lto wm-shadow"/><path class="k3mij9nwy wm-k"/><path class="kjl88pbfm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:drumstick-engrave" /></template>
