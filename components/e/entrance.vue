<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zks0hobcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zks0hobcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:entrance" /></template>
