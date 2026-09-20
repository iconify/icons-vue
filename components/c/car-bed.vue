<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x34kw6p8w.css';
import '../../css/b/bb0f4cb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x34kw6p8w"/><path class="bb0f4cb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:car-bed" /></template>
