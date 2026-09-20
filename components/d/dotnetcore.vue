<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtropbt-f.css';
import '../../css/h/hal2ihy4e.css';
import '../../css/o/o42u20lrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="wtropbt-f"><path class="hal2ihy4e"/><path class="o42u20lrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dotnetcore" /></template>
