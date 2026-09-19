<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp02h-b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pp02h-b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bookmark-stroke-12" /></template>
