<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aui9c_vuc.css';
import '../../css/b/bmmy7ztjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aui9c_vuc"/><path class="bmmy7ztjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-dots-stroke-20" /></template>
