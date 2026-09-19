<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4dd2fb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c4dd2fb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:eject" /></template>
