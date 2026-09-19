<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m2yiegdfw.css';
import '../../css/h/hiuezpb0a.css';
import '../../css/z/zoiufacpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m2yiegdfw"/><path class="hiuezpb0a"/><path clip-rule="evenodd" class="zoiufacpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:crown" /></template>
