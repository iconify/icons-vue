<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m0xrrzbhk.css';
import '../../css/h/hffxopbeb.css';
import '../../css/l/li3jly3hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="m0xrrzbhk"/><circle class="hffxopbeb"/><path class="li3jly3hg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-search" /></template>
