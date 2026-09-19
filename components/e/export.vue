<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj-g8ac3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dj-g8ac3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:export" /></template>
