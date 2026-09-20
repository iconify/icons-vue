<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3d7irbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n3d7irbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:diamond-outline" /></template>
