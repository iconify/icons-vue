<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/ca6l3jo0i.css';
import '../../css/m/mswcqsbra.css';
import '../../css/v/vy55njbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ca6l3jo0i"/><path class="mswcqsbra"/><path class="vy55njbun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crop2-duotone" /></template>
