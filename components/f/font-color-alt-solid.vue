<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o00zo4bbg.css';
import '../../css/y/yrqnibb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o00zo4bbg"/><path clip-rule="evenodd" class="yrqnibb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:font-color-alt-solid" /></template>
