<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hjzzbm_-c.css';
import '../../css/m/mwhwsob7h.css';
import '../../css/n/npufftbla.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="hjzzbm_-c"/><path clip-rule="evenodd" class="mwhwsob7h"/><path class="npufftbla"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:info-circle-filled" /></template>
