<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qygg6abkf.css';
import '../../css/h/h42k6-b2l.css';
import '../../css/v/vd6ip0kos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qygg6abkf wm-a"/><path class="h42k6-b2l wm-k"/><path class="vd6ip0kos wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-down-sketch" /></template>
