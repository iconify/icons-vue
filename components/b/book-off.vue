<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kpj9684_w.css';
import '../../css/j/j062rccnk.css';
import '../../css/w/wobnozssh.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="kpj9684_w"/><path clip-rule="evenodd" class="j062rccnk"/><path clip-rule="evenodd" class="wobnozssh"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:book-off" /></template>
