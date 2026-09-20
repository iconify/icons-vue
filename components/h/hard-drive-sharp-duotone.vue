<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/i4hho8ioh.css';
import '../../css/w/wt2sl3biy.css';
import '../../css/n/nuq8w1bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i4hho8ioh"/><path class="wt2sl3biy"/><path clip-rule="evenodd" class="nuq8w1bat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-drive-sharp-duotone" /></template>
