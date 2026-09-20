<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op4vh8z_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="op4vh8z_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-o-fill" /></template>
