<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/za3tj5b4x.css';
import '../../css/k/kfmx8mkie.css';
import '../../css/p/p0ok30agg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="za3tj5b4x"/><path class="kfmx8mkie"/><path class="p0ok30agg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:eye-closed-print" /></template>
