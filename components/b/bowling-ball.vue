<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfx_ymb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yfx_ymb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bowling-ball" /></template>
