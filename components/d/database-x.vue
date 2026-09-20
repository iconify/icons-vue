<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/x2glrpu2w.css';
import '../../css/h/h90vlqfmf.css';
import '../../css/t/tj6aivbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x2glrpu2w"/><path class="h90vlqfmf"/><ellipse class="tj6aivbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:database-x" /></template>
