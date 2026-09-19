<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gr9m9wk_h.css';
import '../../css/i/is84bqbrt.css';
import '../../css/h/hns4a0bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="gr9m9wk_h"/><path clip-rule="evenodd" class="is84bqbrt"/><path class="hns4a0bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cast-screen" /></template>
