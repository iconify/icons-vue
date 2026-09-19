<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylobwvhsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1280};
const content = `<path class="ylobwvhsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:long-arrow-left" /></template>
