<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pk16079fy.css';
import '../../css/s/ssw2-urzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pk16079fy"/><path class="ssw2-urzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-stats" /></template>
