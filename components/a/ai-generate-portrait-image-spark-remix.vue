<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdszi2i9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gdszi2i9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:ai-generate-portrait-image-spark-remix" /></template>
