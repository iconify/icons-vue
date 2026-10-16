<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ui8-015uj.css';
import '../../css/l/lo86mjbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":57,"height":58};
const content = `<g class="ft5dv1b6b"><path class="ui8-015uj"/><path clip-rule="evenodd" class="lo86mjbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:label-studio" /></template>
