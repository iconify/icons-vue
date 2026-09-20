<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4l-yfbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p4l-yfbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-right-outline" /></template>
