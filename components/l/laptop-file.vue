<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tznxr9bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tznxr9bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:laptop-file" /></template>
