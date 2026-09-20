<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p26na6bbu.css';
import '../../css/u/u5krrmbjh.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p26na6bbu"/><path class="u5krrmbjh"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:color-picker-circle-off" /></template>
