<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy190urnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jy190urnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bicycle-bike-remix" /></template>
