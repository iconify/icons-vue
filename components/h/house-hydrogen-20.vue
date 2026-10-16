<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbx5zccce.css';
import '../../css/h/h1-nu3ycy.css';
import '../../css/q/qlt2pdhtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="h1-nu3ycy"/><path class="qlt2pdhtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-hydrogen-20" /></template>
