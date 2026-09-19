<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g9409uhnn.css';
import '../../css/j/js1fb1lgb.css';
import '../../css/n/n1cw_vbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g9409uhnn"/><path clip-rule="evenodd" class="js1fb1lgb"/><path class="n1cw_vbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:dress" /></template>
