<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/a/aieg73b8w.css';
import '../../css/p/pkjm_57eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path clip-rule="evenodd" class="aieg73b8w"/><path class="pkjm_57eg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:drop-shadow-right" /></template>
