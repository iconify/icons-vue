<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl1hj1dvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xl1hj1dvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:discard" /></template>
