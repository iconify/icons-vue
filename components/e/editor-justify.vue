<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjwheac7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rjwheac7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-justify" /></template>
