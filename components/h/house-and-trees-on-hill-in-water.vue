<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnj3ggbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jnj3ggbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:house-and-trees-on-hill-in-water" /></template>
