<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-82h-3mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b-82h-3mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:envelope-x-thin" /></template>
