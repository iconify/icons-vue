<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydo4l3bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ydo4l3bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hinduism" /></template>
