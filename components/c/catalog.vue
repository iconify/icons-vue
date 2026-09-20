<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bal25inyd.css';
import '../../css/p/pzhd2ofdi.css';
import '../../css/h/ht2qeubdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bal25inyd"/><path class="pzhd2ofdi"/><path class="ht2qeubdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:catalog" /></template>
