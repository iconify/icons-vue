<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5q-5cgz.css';
import '../../css/g/ga_k3d8mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zv5q-5cgz"/><path class="ga_k3d8mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:amazon" /></template>
