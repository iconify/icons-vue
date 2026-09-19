<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd1gm5b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<path class="hd1gm5b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:cloud" /></template>
