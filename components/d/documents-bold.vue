<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/od6evsbxr.css';
import '../../css/f/fp06y8bqm.css';
import '../../css/r/rsvmd3nqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="od6evsbxr"/><path class="fp06y8bqm"/><path class="rsvmd3nqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:documents-bold" /></template>
