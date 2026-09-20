<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/e4fgyobzl.css';
import '../../css/q/qte5fcb6h.css';
import '../../css/o/ooe5hubum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e4fgyobzl"/><path class="qte5fcb6h"/><path class="ooe5hubum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cable" /></template>
