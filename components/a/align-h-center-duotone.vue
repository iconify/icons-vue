<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cwnhso7ti.css';
import '../../css/r/rsgd5xbzn.css';
import '../../css/w/wcnkyxb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cwnhso7ti"/><path class="rsgd5xbzn"/><path class="wcnkyxb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-h-center-duotone" /></template>
