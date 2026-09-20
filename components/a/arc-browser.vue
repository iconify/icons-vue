<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bohz0aboj.css';
import '../../css/g/gegijw-bc.css';
import '../../css/k/kvlujpe3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bohz0aboj"/><path class="gegijw-bc"/><path class="kvlujpe3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arc-browser" /></template>
