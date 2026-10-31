<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe9q90bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xe9q90bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-window" /></template>
