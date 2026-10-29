<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ekqmbnb8e.css';
import '../../css/c/ck8dhpbcc.css';
import '../../css/h/hje6bbbsd.css';
import '../../css/a/acoval0gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ekqmbnb8e wm-k"/><path class="ck8dhpbcc wm-a"/><path class="hje6bbbsd wm-k"/><path class="acoval0gz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:contactless-sketch" /></template>
