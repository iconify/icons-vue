<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fbg066znp.css';
import '../../css/f/fqjm84fig.css';
import '../../css/m/mp6us146y.css';
import '../../css/o/ogqgbeb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fbg066znp wm-k"/><path class="fqjm84fig wm-a"/><path class="mp6us146y wm-k"/><path class="ogqgbeb3t wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:indent-decrease-sketch" /></template>
