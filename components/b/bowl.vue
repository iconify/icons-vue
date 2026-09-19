<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff2isvjvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ff2isvjvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:bowl" /></template>
