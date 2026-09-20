<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/to4gwhjvi.css';
import '../../css/z/zcsfiacrb.css';
import '../../css/o/otto5l3wd.css';
import '../../css/c/cb7u8-bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="to4gwhjvi"/><path class="zcsfiacrb"/><path clip-rule="evenodd" class="otto5l3wd"/><path class="cb7u8-bvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:file-pdf-filled" /></template>
