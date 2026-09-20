<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omo6m3bky.css';
import '../../css/n/nttd48xax.css';
import '../../css/z/zj8owxbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":400};
const content = `<g class="omo6m3bky"><path class="nttd48xax"/><path class="zj8owxbjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:bithound" /></template>
