<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-bjp6n_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="r-bjp6n_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:flame" /></template>
