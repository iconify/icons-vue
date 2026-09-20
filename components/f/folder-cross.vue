<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1dviszv.css';
import '../../css/v/vr96f8b4k.css';
import '../../css/j/jx_9pv92d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="vr96f8b4k"/><path class="jx_9pv92d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-cross" /></template>
