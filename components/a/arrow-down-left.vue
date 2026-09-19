<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/ntqqlf_wk.css';
import '../../css/m/m0bhoobwp.css';
import '../../css/l/lejiw1pae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ntqqlf_wk"/><path class="m0bhoobwp"/><path class="lejiw1pae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-down-left" /></template>
