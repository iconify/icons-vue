<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlvh1icjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qlvh1icjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ctrl-a" /></template>
