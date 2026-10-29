<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c6f3gjbpc.css';
import '../../css/t/tm9rjtb7h.css';
import '../../css/o/ou--dacom.css';
import '../../css/q/qo_bukb7u.css';
import '../../css/n/nlxhy-_vt.css';
import '../../css/h/h9f1s1bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c6f3gjbpc"/><path class="tm9rjtb7h wm-k"/><path class="ou--dacom wm-s"/><path class="qo_bukb7u wm-k"/><path class="nlxhy-_vt wm-a"/><path class="h9f1s1bpy wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-clock-sketch" /></template>
