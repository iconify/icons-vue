<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fel8qbbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fel8qbbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:image-flip-horizontal" /></template>
