<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqmfhq6dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cqmfhq6dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:comment-dots" /></template>
