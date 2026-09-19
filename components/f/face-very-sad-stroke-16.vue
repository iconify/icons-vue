<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3une8b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u3une8b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-very-sad-stroke-16" /></template>
