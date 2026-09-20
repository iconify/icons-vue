<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fcdm4-b9o.css';
import '../../css/n/nc20dabau.css';
import '../../css/i/i2zatytzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fcdm4-b9o"/><path class="nc20dabau"/><path class="i2zatytzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-up-filled" /></template>
