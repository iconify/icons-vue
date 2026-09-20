<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nmxf9tbnv.css';
import '../../css/n/n_4r7zbss.css';
import '../../css/g/glbe0wbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nmxf9tbnv"/><path class="n_4r7zbss"/><path class="glbe0wbll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:link-2" /></template>
