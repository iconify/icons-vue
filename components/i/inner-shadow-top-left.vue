<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/i/i--wlebtf.css';
import '../../css/b/biaplyhuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="gopnm44um"><path clip-rule="evenodd" class="i--wlebtf"/><path class="biaplyhuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:inner-shadow-top-left" /></template>
