<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nl020ey9a.css';
import '../../css/w/wt121qu2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="nl020ey9a"/><path class="wt121qu2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:background-color" /></template>
