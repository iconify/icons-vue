<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0v5ewb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j0v5ewb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:add" /></template>
