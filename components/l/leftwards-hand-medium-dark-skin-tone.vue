<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye_28eu0i.css';
import '../../css/j/jzkzakb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ye_28eu0i"/><path class="jzkzakb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leftwards-hand-medium-dark-skin-tone" /></template>
