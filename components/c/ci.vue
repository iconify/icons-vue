<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qqa_bcb1r.css';
import '../../css/l/lyeaxac2j.css';
import '../../css/p/pmz80t_au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qqa_bcb1r"/><path class="lyeaxac2j"/><path class="pmz80t_au"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:ci" /></template>
