<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g-hs3vbsc.css';
import '../../css/e/elyi5abmp.css';
import '../../css/i/iqliabezm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g-hs3vbsc"/><path class="elyi5abmp"/><path class="iqliabezm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:book-open" /></template>
