<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmg8jk-cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cmg8jk-cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleloaderseven" /></template>
