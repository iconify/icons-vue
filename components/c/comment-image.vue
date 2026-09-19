<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-1qd4bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="f-1qd4bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-image" /></template>
