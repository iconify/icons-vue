<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/btwzuobxo.css';
import '../../css/z/zjwhn7b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="folder-open-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="btwzuobxo"/><path class="zjwhn7b_n"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:folder-open-outline" /></template>
