<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml5gl5ako.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="ml5gl5ako"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:comment-o" /></template>
