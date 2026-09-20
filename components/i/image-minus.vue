<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kzmnvikyr.css';
import '../../css/k/kaaj88bma.css';
import '../../css/k/kiwzkfnae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kzmnvikyr"/><path clip-rule="evenodd" class="kaaj88bma"/><path class="kiwzkfnae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-minus" /></template>
