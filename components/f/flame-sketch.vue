<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z8at5w8mn.css';
import '../../css/d/d9i2tmb1h.css';
import '../../css/z/z9j954boo.css';
import '../../css/f/fy38hacrj.css';
import '../../css/l/leyxddi5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z8at5w8mn"/><path class="d9i2tmb1h wm-k"/><path class="wm-a z9j954boo"/><path class="fy38hacrj wm-k"/><path class="leyxddi5o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flame-sketch" /></template>
