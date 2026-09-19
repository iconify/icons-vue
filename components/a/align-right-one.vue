<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3ivccum.css';
import '../../css/g/g5oougblb.css';
import '../../css/j/jjkm7ug5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="g5oougblb"/><path class="jjkm7ug5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-right-one" /></template>
