<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/w/w6r6sxrzo.css';
import '../../css/o/omlunobmw.css';
import '../../css/b/bhx3wd61g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="w6r6sxrzo"/><path class="omlunobmw"/><path class="bhx3wd61g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:code" /></template>
