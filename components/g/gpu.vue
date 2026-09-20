<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cd_x0n3ko.css';
import '../../css/h/h7zu85-xk.css';
import '../../css/d/dgg_3-5dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cd_x0n3ko"/><circle class="h7zu85-xk"/><circle class="dgg_3-5dy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:gpu" /></template>
