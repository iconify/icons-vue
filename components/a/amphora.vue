<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/kdu4ius8f.css';
import '../../css/f/f2gwe7byg.css';
import '../../css/z/zpr52sbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kdu4ius8f"/><path class="f2gwe7byg"/><path class="zpr52sbwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:amphora" /></template>
