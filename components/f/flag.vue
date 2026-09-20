<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vvk71lb-z.css';
import '../../css/v/v4xpcu_js.css';
import '../../css/d/dt5g15b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="vvk71lb-z"/><path clip-rule="evenodd" class="v4xpcu_js"/><path clip-rule="evenodd" class="dt5g15b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:flag" /></template>
