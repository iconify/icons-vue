<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt55yfbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kt55yfbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-generate-landscape-image-spark-remix" /></template>
