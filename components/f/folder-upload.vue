<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jexdvubgo.css';
import '../../css/i/ixrnlcbfj.css';
import '../../css/r/raobunbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="jexdvubgo"/><path class="ixrnlcbfj"/><path class="raobunbaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-upload" /></template>
