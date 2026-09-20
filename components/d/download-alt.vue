<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/n/n1i6_2bkg.css';
import '../../css/z/zukmucctw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="n1i6_2bkg"/><path class="zukmucctw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:download-alt" /></template>
