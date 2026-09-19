<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7un0iy0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j7un0iy0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hammer" /></template>
