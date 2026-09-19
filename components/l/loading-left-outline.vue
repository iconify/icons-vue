<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nzacwof9r.css';
import '../../css/o/o7kac3b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="loadgin-left-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="nzacwof9r"/><path class="o7kac3b2m"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:loading-left-outline" /></template>
