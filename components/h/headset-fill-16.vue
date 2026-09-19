<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czr7ry1ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="czr7ry1ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:headset-fill-16" /></template>
