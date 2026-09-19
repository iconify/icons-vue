<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/frt9n6w4o.css';
import '../../css/x/xr2clcb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="frt9n6w4o"/><path class="xr2clcb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:landmark-solid" /></template>
