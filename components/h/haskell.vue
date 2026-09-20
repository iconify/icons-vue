<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bof77n6om.css';
import '../../css/m/mn9zp8bxl.css';
import '../../css/j/jr5b5nohz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bof77n6om"/><path class="mn9zp8bxl"/><path class="jr5b5nohz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:haskell" /></template>
