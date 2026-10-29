<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n6cy9hz8y.css';
import '../../css/f/fr25ybbad.css';
import '../../css/h/h6orqybed.css';
import '../../css/o/o3d4k3blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n6cy9hz8y"/><path class="fr25ybbad"/><path class="h6orqybed wm-a"/><path class="o3d4k3blk wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:files-sketch" /></template>
