<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jexdvubgo.css';
import '../../css/d/dmnntrbnl.css';
import '../../css/j/jayyg5beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="jexdvubgo"/><path class="dmnntrbnl"/><path class="jayyg5beu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:folder-withdrawal" /></template>
