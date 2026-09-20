<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pkr_a7gda.css';
import '../../css/e/ed5rao9ma.css';
import '../../css/g/g0c7m3b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pkr_a7gda"/><path class="ed5rao9ma"/><path clip-rule="evenodd" class="g0c7m3b9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-music-bold" /></template>
