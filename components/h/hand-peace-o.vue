<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czb3gi03f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="czb3gi03f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-peace-o" /></template>
