<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5zd7xsej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l5zd7xsej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:anguished-face-with-spots" /></template>
