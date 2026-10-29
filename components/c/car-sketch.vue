<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ic0jf5bor.css';
import '../../css/u/uq73d1qjn.css';
import '../../css/s/swzt5ac_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ic0jf5bor wm-k"/><path class="uq73d1qjn wm-k"/><path class="swzt5ac_x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:car-sketch" /></template>
