<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/igz61olkm.css';
import '../../css/p/p749f_u1o.css';
import '../../css/z/z6hf0nvwr.css';
import '../../css/f/fmg8n-8ff.css';
import '../../css/i/i9fjefbqx.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="igz61olkm"/><path class="p749f_u1o"/><path clip-rule="evenodd" class="z6hf0nvwr"/><path class="fmg8n-8ff"/><path class="i9fjefbqx"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:bicycle-off" /></template>
