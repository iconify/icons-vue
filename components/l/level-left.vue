<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkyb1huxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rkyb1huxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:level-left" /></template>
