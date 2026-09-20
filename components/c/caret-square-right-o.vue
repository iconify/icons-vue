<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cflr1ab0i.css';
import '../../css/u/uu2hu__dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cflr1ab0i"/><path class="uu2hu__dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:caret-square-right-o" /></template>
