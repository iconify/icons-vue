<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_v47x3vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j_v47x3vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:filamentphp" /></template>
