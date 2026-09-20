<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzdlp6bkl.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/l/lj70h7b9m.css';
import '../../css/o/ozbpad-uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zzdlp6bkl"/><g class="sxsjrzbyv"><path class="lj70h7b9m"/><path class="ozbpad-uv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:eject-button" /></template>
