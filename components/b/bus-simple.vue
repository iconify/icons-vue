<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0fis8b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b0fis8b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bus-simple" /></template>
