<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cshvsweet.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/m/mfug5ibpq.css';
import '../../css/c/c66ezsb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cshvsweet"/><g class="ij2x_72vy"><path class="mfug5ibpq"/><path class="c66ezsb2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:code-editor" /></template>
