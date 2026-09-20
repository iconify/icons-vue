<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mn60u_xaa.css';
import '../../css/s/s72jc8bgn.css';
import '../../css/b/bf7l22bfs.css';
import '../../css/v/vkf35_b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="mn60u_xaa"/><path class="s72jc8bgn"/><path class="bf7l22bfs"/><path class="vkf35_b2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:enter" /></template>
