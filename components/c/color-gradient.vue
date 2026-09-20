<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/damgo-bgt.css';
import '../../css/d/d52rbb3lm.css';
import '../../css/w/wk121w0kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="damgo-bgt"/><path class="d52rbb3lm"/><path class="wk121w0kk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:color-gradient" /></template>
