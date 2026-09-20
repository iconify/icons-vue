<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1dviszv.css';
import '../../css/j/jx_9pv92d.css';
import '../../css/m/m_5zghb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="jx_9pv92d"/><path class="m_5zghb_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder2" /></template>
