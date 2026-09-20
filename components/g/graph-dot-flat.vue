<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ceroknbfa.css';
import '../../css/m/mbjxabcpy.css';
import '../../css/d/djdfu5b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ceroknbfa"/><path class="mbjxabcpy"/><path class="djdfu5b9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:graph-dot-flat" /></template>
