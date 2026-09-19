<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1uwanbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p1uwanbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:box-3d-stroke-12" /></template>
