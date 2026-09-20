<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lgab0wbtr.css';
import '../../css/h/hf4x25m7i.css';
import '../../css/g/gvl74m1sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lgab0wbtr"/><path clip-rule="evenodd" class="hf4x25m7i"/><path class="gvl74m1sh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart2-duotone" /></template>
