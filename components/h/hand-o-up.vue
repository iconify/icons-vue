<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dufl35bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="dufl35bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-o-up" /></template>
