<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgn0limsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jgn0limsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-line-fill-12" /></template>
