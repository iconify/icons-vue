<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/cm4ry-biv.css';
import '../../css/b/bk0qoubdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="chatbubbles-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="cm4ry-biv"/><path class="bk0qoubdl"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:chatbubbles-outline" /></template>
