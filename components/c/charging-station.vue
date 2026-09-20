<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1lijt-zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j1lijt-zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:charging-station" /></template>
