<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur_xiv5wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="ur_xiv5wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-list" /></template>
