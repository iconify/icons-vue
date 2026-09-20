<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1dviszv.css';
import '../../css/r/read_2bcl.css';
import '../../css/j/jx_9pv92d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="read_2bcl"/><path class="jx_9pv92d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-minus3" /></template>
