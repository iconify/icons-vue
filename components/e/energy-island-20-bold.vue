<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdh5c-m9v.css';
import '../../css/b/bf8izsb7o.css';
import '../../css/q/qdhnwmbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdh5c-m9v"/><path class="bf8izsb7o"/><path class="qdhnwmbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-island-20-bold" /></template>
