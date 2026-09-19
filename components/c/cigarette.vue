<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4o3fs57g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="j4o3fs57g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cigarette" /></template>
