<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ahht-lblb.css';
import '../../css/v/v9-vf_b4p.css';
import '../../css/a/ad0valb_r.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ahht-lblb"/><path clip-rule="evenodd" class="v9-vf_b4p"/><path clip-rule="evenodd" class="ad0valb_r"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:dollar-off" /></template>
