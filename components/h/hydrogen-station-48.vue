<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a23qezmoi.css';
import '../../css/h/hokkqjb4r.css';
import '../../css/d/dy4drqbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a23qezmoi"/><path class="hokkqjb4r"/><path class="dy4drqbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-station-48" /></template>
