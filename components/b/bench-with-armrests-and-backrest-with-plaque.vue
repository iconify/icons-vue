<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmnv41bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jmnv41bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bench-with-armrests-and-backrest-with-plaque" /></template>
