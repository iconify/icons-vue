<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/q/q-eob553s.css';
import '../../css/o/oztyr0b6l.css';
import '../../css/o/obt5sdblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="q-eob553s"/><path class="oztyr0b6l"/><path class="obt5sdblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:filter-edit" /></template>
