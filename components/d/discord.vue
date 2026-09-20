<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/z/zpg5x16lp.css';
import '../../css/h/hbak2v8ug.css';
import '../../css/c/cwo89ng1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="h01tyzbfu"><path class="zpg5x16lp"/><path class="hbak2v8ug"/><path class="cwo89ng1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:discord" /></template>
