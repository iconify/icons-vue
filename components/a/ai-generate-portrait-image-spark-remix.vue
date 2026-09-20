<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bej3u-s3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bej3u-s3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-generate-portrait-image-spark-remix" /></template>
