<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/n3e2bl-1s.css';
import '../../css/k/kozsdpb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="logout-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="n3e2bl-1s"/><path class="kozsdpb7i"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:logout-outline" /></template>
