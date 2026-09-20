<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y95t8mryw.css';
import '../../css/v/vr3o4bbfg.css';
import '../../css/l/lg0q5_b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y95t8mryw"/><path class="vr3o4bbfg"/><path class="lg0q5_b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:beach-flat" /></template>
