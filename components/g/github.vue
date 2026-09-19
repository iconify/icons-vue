<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdptjablm.css';
import '../../css/n/nsdrsoimu.css';
import '../../css/l/l88o95l5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="tdptjablm"><path clip-rule="evenodd" class="nsdrsoimu"/><path class="l88o95l5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:github" /></template>
