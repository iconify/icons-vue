<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/d/di1zu1bph.css';
import '../../css/f/fvc61obyz.css';
import '../../css/b/b0fz9dbol.css';
import '../../css/l/lg5ifb00l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="di1zu1bph"/><rect class="fvc61obyz"/><path class="b0fz9dbol"/><path class="lg5ifb00l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:computer" /></template>
