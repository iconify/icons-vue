<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi8-49b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="yi8-49b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:butterfly" /></template>
