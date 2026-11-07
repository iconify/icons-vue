<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv08lsi2x.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/f/f1k3q-bzm.css';
import '../../css/i/i6x-msbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iv08lsi2x"/><g class="xtpeb-edw"><path class="f1k3q-bzm"/><path class="i6x-msbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-down-right-bold-duotone" /></template>
