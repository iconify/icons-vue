<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lbj85ed8c.css';
import '../../css/z/zzhn1q2in.css';
import '../../css/g/g3kzkz79z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lbj85ed8c wm-k"/><path class="wm-a zzhn1q2in"/><path class="g3kzkz79z wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:holi-splash-sketch" /></template>
