<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t80g4uv5w.css';
import '../../css/x/xtau0h03z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t80g4uv5w"/><path class="xtau0h03z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-up-20-bold" /></template>
