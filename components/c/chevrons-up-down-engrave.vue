<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p1d1xqfpi.css';
import '../../css/r/ri-cmgb7b.css';
import '../../css/s/shkjd1brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p1d1xqfpi"/><path class="ri-cmgb7b wm-shadow"/><path class="shkjd1brf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-up-down-engrave" /></template>
