<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1dviszv.css';
import '../../css/w/w-6yckbxi.css';
import '../../css/j/jx_9pv92d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="w-6yckbxi"/><path class="jx_9pv92d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-add3" /></template>
