<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbgu8eb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hbgu8eb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:agent-ai" /></template>
