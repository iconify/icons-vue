<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hw50r1bhi.css';
import '../../css/q/q95augsqe.css';
import '../../css/y/y_wvf86zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hw50r1bhi"/><path clip-rule="evenodd" class="q95augsqe"/><path class="y_wvf86zn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:heart-hands-dark" /></template>
