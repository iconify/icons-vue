<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jryms8byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jryms8byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dash-stroke-16" /></template>
