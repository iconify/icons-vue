<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4k-vfb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v4k-vfb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:engineering-group" /></template>
