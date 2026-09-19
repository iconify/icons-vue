<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/yso__w5go.css';
import '../../css/m/mcjp-yqnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="loading-right-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="yso__w5go"/><path class="mcjp-yqnp"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:loading-right-outline" /></template>
